# LEVEL UP v0.2 — APK build with GitHub Actions

Mobile-first, offline-capable fitness RPG packaged with Capacitor.

## Upload from phone
1. Create a GitHub repository.
2. Upload the **contents** of this ZIP into the repository root (not the ZIP itself, and not inside another folder).
3. Verify `package.json`, `index.html`, `app.js`, `styles.css`, and `.github/workflows/build-apk.yml` are visible at the root.
4. Open Actions → Build LEVEL UP APK → Run workflow.
5. Download the `LEVEL-UP-debug-apk` artifact, unzip it, then install `app-debug.apk`.

## Features
- Local profile welcome/login animation (no account/network required)
- Five tabs: Home, Training, Nutrition, Progress, Profile
- Home/Gym selector, workout timer, exercise swap and animated offline guide
- Online exercise video tutorial search (internet required)
- Offline nutrition calculator, food logging and cooking recipes
- Local progress data and JSON backup/restore

Exercise tutorial animation is an illustrative motion graphic, not a real recorded video.
