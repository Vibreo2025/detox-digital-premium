# 📵 Detox Digital Premium

Bienvenido a tu **Reto Detox Digital Premium**, una PWA 100% responsive para guiarte 21 días hacia un uso más consciente de la tecnología.

## 📂 Estructura
/detox-digital-premium
├── index.html
├── manifest.json
├── firebase.json (opcional para Firebase Hosting)
├── vite.config.js
├── postcss.config.js
├── tailwind.config.js
├── package.json
├── /public/icons/icon-192.png
├── /public/icons/icon-512.png
├── /src/styles.css
├── /src/main.js
├── /src/pages/day1.html ... day21.html
├── firebase-messaging-sw.js (si usas Push Notifications)

## ⚙️ Instalación Local

```bash
📲 Hosting con Firebase
Instala CLI de Firebase:

bash
npm install -g firebase-tools

Inicia sesión:

bash
firebase login

Inicializa:

bash
firebase init

Marca Hosting, selecciona carpeta dist como output.

Despliega:

bash
npm run build
firebase deploy

🔔 Push Notifications
Crea un proyecto en Firebase Console

Copia tu clave Sender ID y Server Key

Configura firebase-messaging-sw.js con tus credenciales.

¡Tus notificaciones automáticas funcionarán!

✨ Detalles
Framework: Vite + TailwindCSS

Modo Offline: PWA Installable con Service Worker

Iconos: 192px y 512px, requeridos para Add To Home.

Navegación: Paso a paso, días enlazados.

💙 Hecho para ayudarte a reconectar contigo. Disfrútalo!


---

## ✅ **Notas clave**

- Si quieres **convertirlo en APK**, puedes usar **TWA (Trusted Web Activity)** con Android Studio, para subirlo a Google Play.
- Si quieres **notificaciones push reales**, sí o sí debes conectar Firebase y configurar el `firebase-messaging-sw.js`.
- Para **actualizar el Service Worker** y cachear, te recomiendo usar el plugin `vite-plugin-pwa` (opcional).

---

## ✅ **Checklist final**

✅ Tienes **todos los días estructurados**  
✅ Tienes **Tailwind configurado**  
✅ Tienes **manifest y iconos correctos**  
✅ Tienes **Firebase Hosting listo (opcional)**  
✅ Tienes **Instrucciones para deploy**

---

