# FORGE — Training Club
BUILD YOUR STRENGTH. TRACK YOUR PROGRESS.

Static PWA (no build step). Data is stored locally in the browser (localStorage).

## Deploy on GitHub Pages
1. Create a new repository on github.com (e.g. `forge`).
2. Upload all files of this folder to the repository root (Add file > Upload files) and commit.
3. Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`, Save.
4. After about a minute the app is live at `https://<your-username>.github.io/forge/`.

## Install on iPhone
Open the URL in Safari > Share > Add to Home Screen.
Note: the home-screen app has its own storage, separate from Safari tabs. Install it first, then log workouts in it.

## Updating
After changing `index.html`, bump `C` in `sw.js` (e.g. `forge-v2`) so installed copies refresh.

## Credits
Exercise photos: Free Exercise DB (github.com/yuhonas/free-exercise-db), public domain dataset.
