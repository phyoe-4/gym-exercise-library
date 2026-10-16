GYM EXERCISE LIBRARY — PERSONAL WEB APP
=======================================

FILES
index.html   Main page
style.css    Theme and layout
app.js       Library logic and IndexedDB storage
vendor/      Local JSZip library (used for backups)

TEST ON A COMPUTER
Open index.html in Chrome or Edge. For the most reliable persistent storage,
run it on http://localhost or a hosted HTTPS site instead of file://.

OPTIONAL LOCAL SERVER
From this folder, run: python -m http.server 8080
Then open http://localhost:8080 in a browser.

TEST ON ANDROID (NO INSTALLATION)
Publish these files together to a static HTTPS hosting service (e.g. GitHub
Pages, Netlify, Cloudflare Pages). Open your site's HTTPS address in Android
Chrome. All imported media and exercises remain on that browser/device.
This ZIP is source code, not an already-published website.

FEATURES
- Add, edit, delete and search exercises
- Muscle-group filter, editable muscle group names
- Multiple image, GIF and video uploads per exercise
- Choose gallery cover, rearrange and remove individual media
- Equipment, difficulty, sets, reps, rest, notes and instructions
- Persistent local browser storage (IndexedDB)
- Export / restore full library with media in ZIP format

IMPORTANT
- Clearing browser site data can delete all exercises and media. Export backups.
- Multiple devices do not sync. Cloud sync is not implemented yet.
- Very large videos may be rejected by browser storage quotas, or by available RAM
  during backup creation. Compress videos before importing for best performance.
- Restoring a ZIP backup REPLACES the current library in that browser.
