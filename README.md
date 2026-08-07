# EDA Call Desk PWA

Free, static iPhone PWA for Emergency Dental of America call-center reference and scheduling.

## Install on iPhone
1. Deploy this folder to any HTTPS static host (GitHub Pages is free).
2. Open the live site in Safari.
3. Tap Share -> Add to Home Screen -> Add.
4. Launch EDA Call Desk from the Home Screen.

## Offline
The service worker caches the app shell so the core directory and scheduling tools can remain usable when connectivity drops. External phone and Apple Maps actions may still require network/service availability.

## Updating
Replace `index.html`, increment the cache name in `service-worker.js`, and redeploy.
