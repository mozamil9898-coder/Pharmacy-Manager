PHARMACY MANAGER - MOBILE PWA
This version uses IndexedDB for local records, plus JSON backup/restore.
For reliable installation and offline use, publish the files to a free HTTPS static host (e.g. GitHub Pages), then open that HTTPS address in Chrome and choose Install app / Add to Home screen.

Do NOT open index.html directly from the Files app for final use. A PWA needs HTTPS (or localhost) for service worker installation and offline caching.

FREE HOSTING STEPS (GitHub Pages):
1. Create a GitHub account and a new PUBLIC repository.
2. Upload index.html, manifest.webmanifest, sw.js and the complete icons folder.
3. Repository Settings > Pages > Deploy from a branch > main > /(root) > Save.
4. Wait for the published https://... address.
5. Open it in Android Chrome, use menu > Install app (or Add to Home screen).
6. Open once online; then test airplane mode.
7. Add a test medicine, close/reopen the installed app, and verify it remains.
8. Download a backup before entering real inventory.

DATA: Records are stored only in this phone's browser database. Do not clear Chrome site data, use Incognito, or uninstall/reset Chrome without a backup. Browser persistence is requested but backups remain essential.

This starter includes dashboard, medicine records, stock and expiry alerts, edit/delete, backup/restore. Sales, purchases, supplier/customer ledgers and profit reports are future modules. Not a certified pharmacy/POS system.
