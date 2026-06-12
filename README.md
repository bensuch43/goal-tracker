# Goal Tracker PWA

A daily SMART goal tracker, installable as a Progressive Web App.

## Deploy to GitHub Pages

1. **Create a new repo** on GitHub (e.g. `goal-tracker`)

2. **Upload all files** — keep the folder structure exactly as-is:
   ```
   index.html
   manifest.json
   sw.js
   icons/
     icon-192.png
     icon-512.png
   ```

3. **Enable GitHub Pages**:
   - Go to repo → Settings → Pages
   - Source: `Deploy from a branch`
   - Branch: `main` / `root`
   - Save

4. Your app will be live at:
   `https://<your-username>.github.io/goal-tracker/`

## Installing on your phone

### Android (Chrome)
- Open the URL in Chrome
- Tap the **three-dot menu** → "Add to Home screen"
- Or tap the **install banner** if it appears

### iPhone (Safari)
- Open the URL in Safari
- Tap the **Share button** (box with arrow)
- Scroll down and tap **"Add to Home Screen"**

## Notes
- All data is stored locally on your device (localStorage)
- The app works fully offline once installed
- Clearing browser/app data will reset your goals and history
