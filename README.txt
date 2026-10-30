NOTORIOUS SENSI PRO — PWA package

FILES
- index.html: the app
- manifest.webmanifest: install metadata
- sw.js: offline cache/service worker
- icon-192.png and icon-512.png: app icons

INSTALL ON ANDROID
A Progressive Web App generally needs to be served from HTTPS (or localhost). Opening index.html directly as a file will not enable the install prompt.

Simple route:
1. Upload the contents of this folder to a static HTTPS host (for example GitHub Pages or Netlify).
2. Open the hosted site in Chrome on Android.
3. Open Chrome's ⋮ menu and choose "Install app" or "Add to Home screen".
4. Launch NOTORIOUS SENSI PRO from the new home-screen icon.

This is an installable web app, not a signed APK. For a Play Store / APK build, a separate Android packaging step is needed.
