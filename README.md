# Expense Manager Web App

Bilingual Arabic/English expense tracker, designed as an installable PWA for iPhone Safari.

## Deploy with GitHub Pages
1. Create a GitHub account and sign in.
2. Create a new public repository named `expense-manager`.
3. Upload `index.html`, `manifest.json`, `sw.js`, and `icon.svg` to the repository root.
4. Open repository Settings → Pages.
5. Under Build and deployment choose "Deploy from a branch", branch `main`, folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. The URL will look like `https://YOUR-USERNAME.github.io/expense-manager/`.
7. Open that URL in Safari on iPhone → Share → Add to Home Screen.

## Notes
- The app stores records in the browser's localStorage on the current device/browser.
- This first web version does not sync between devices and is not a replacement for a server backup.
- It is an installable web app (PWA), not an App Store IPA.
