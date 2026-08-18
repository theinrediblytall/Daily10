DAILY 10 PWA

This is an installable Progressive Web App package.

Important: Chrome on Android requires the app to be served over HTTPS (or localhost) before the install option will appear. Opening these files directly from Downloads will still run the timer, but Chrome normally will not install it as a PWA from file://.

Files:
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png

Once hosted at an HTTPS address:
1. Open the address in Chrome on your Samsung Galaxy.
2. Chrome menu (⋮) > Add to Home screen / Install app.
3. After first load/install, the service worker caches the app for offline use.
