CivilKit v1.1.0 – Civil engineering / architecture / draughtsman toolkit (offline web app)

HOW TO PUT IT ONLINE (same as WallCAD):
1. On GitHub (civilcad) create a new repository, e.g. "civilkit".
2. Upload ALL files from this folder (index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png).
3. Settings -> Pages -> Branch: main / root -> Save.
4. Open https://civilcad.github.io/civilkit/ on your phone in Chrome -> menu -> "Install app" / "Add to Home screen".
   (Camera, AR, GPS and sensors need the HTTPS link – they will not work from a file opened directly.)

UPDATING LATER:
- Change VERSION in sw.js (e.g. civilkit-v1.0.1) and APP_VERSION in index.html, upload, then in the app:
  About & Updates -> Check for updates.

NOTES:
- AR Tape Measure needs Chrome on an ARCore-supported Android phone (most mid/high-range phones).
- All other tools work on any modern phone. Calculators also work on PC.
