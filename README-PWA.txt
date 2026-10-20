CT Voxel-Rechner als PWA fuer Android und iOS

Dateien gemeinsam in denselben Webordner hochladen:
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png
- apple-touch-icon.png

Wichtig:
- Die App muss ueber HTTPS oder lokal ueber localhost bereitgestellt werden.
- Ein direktes Oeffnen der index.html als file:// aktiviert den Service Worker nicht.

Android:
1. Seite in Chrome oeffnen.
2. Browsermenue oeffnen.
3. "App installieren" oder "Zum Startbildschirm hinzufuegen" waehlen.

iPhone/iPad:
1. Seite in Safari oeffnen.
2. Teilen-Schaltflaeche antippen.
3. "Zum Home-Bildschirm" waehlen.

Nach dem ersten erfolgreichen Laden werden die App-Dateien fuer den Offline-Betrieb gespeichert.
