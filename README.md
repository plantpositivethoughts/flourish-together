# 🌿 Floreamus Una

*Let us flourish together.* A free plant-care and self-care app that runs in the browser and installs to your phone's home screen.

**Live app:** https://plantpositivethoughts.github.io/flourish-together/

## Features
- **Welcome screens** for first-time users
- **Plant photos** stored on-device, included in backups
- **Seasonal watering**: schedules adjust for winter, spring, summer and autumn
- **One-minute breath**: a guided breathing moment
- **Plant collection** with types, light, notes and watering intervals
- **Today view** showing which plants need water, with one-tap watering
- **Daily check-in**: mood, self-care habits, a short journal note
- **Growth view**: check-in streak, plants cared for this week, 7-day mood chart, journal history
- **Works offline** and installs like an app (PWA)
- **Private**: all data stays on your device (export/import backups in Settings)
- Light and dark mode

## Cost: £0
No server, no database, no app store fees. It's plain HTML/CSS/JavaScript hosted free on GitHub Pages.

## Put it on GitHub (from a phone or computer)
1. Sign in at github.com and tap **New repository**. Name it `floreamus-una`, set it to **Public**, tick **Add a README**, and create it.
2. Tap **Add file → Upload files** and upload `index.html`, `manifest.json`, `sw.js`, `icon.svg` (and this `README.md`, replacing the default). Commit.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two your app is live at `https://YOUR-USERNAME.github.io/floreamus-una/`.
5. Open that link on your phone → **Share → Add to Home Screen** (iPhone) or **Install app** (Android).

## Updating
Edit or re-upload files on GitHub; Pages redeploys automatically. Bump `CACHE` in `sw.js` (e.g. `v2`) when you change files so phones pick up the new version.

## Ideas for later (still free)
- Plant photos stored on-device (IndexedDB)
- Seasonal care tips (less water in winter)
- Custom domain via GitHub Pages
- Sync across devices with a free tier backend (e.g. Supabase) — optional
