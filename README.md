# LEVEL UP — Offline Fitness RPG APK

This project builds an Android debug APK using GitHub Actions, entirely in the cloud. You can build it using a phone.

## Upload correctly (important)
1. Create a GitHub repository.
2. Extract this ZIP.
3. Upload **all the files inside this folder**, not the `LEVEL_UP_FIXED` parent folder itself. `package.json` and `.github` must be at the repository root.
4. In GitHub, open **Actions** → **Build LEVEL UP APK** → **Run workflow**. (A push to main/master also triggers a build.)
5. When complete, open the run and download the artifact named `LEVEL-UP-debug-apk`.
6. Extract the artifact ZIP and install `app-debug.apk` on your Android device.

The workflow also detects the earlier nested folder layout (`LEVEL_UP_GITHUB/package.json`) to help recover from the previous upload mistake.

## Local app
- App source is plain HTML/CSS/JavaScript.
- Capacitor packages it as Android.
- The app is intended to operate offline; the GitHub build and APK download require internet.
- App ID: `com.matty.levelup`.
