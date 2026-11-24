# LEVEL UP — Offline Fitness RPG (Android build via GitHub)

This repository contains the offline-first web prototype and a GitHub Actions workflow that compiles it into an Android APK. You do not need Android Studio or a computer; GitHub Actions builds it in the cloud.

## Build APK using your phone
1. Create a GitHub repository (choose **Public** or **Private**).
2. Upload the contents of this project ZIP to the repository root (make sure `.github/workflows/build-apk.yml` is included).
3. Open the repository's **Actions** tab. If GitHub asks, enable Actions.
4. Select **Build LEVEL UP APK** and tap **Run workflow** (or let the first push trigger it).
5. Wait for the run to finish with a green check.
6. Open that workflow run, scroll to **Artifacts**, and download `LEVEL-UP-debug-apk`.
7. Extract the artifact ZIP, open `app-debug.apk` on Android, and approve installing from that source if Android prompts.

## Notes
- Debug APK; suitable for personal testing, not Play Store publishing.
- App content and core functions are bundled locally. Internet is needed only for GitHub's build and downloading the APK.
- App ID: `com.matty.levelup`.
- Future builds can be produced by pushing changes to `main` or running the workflow manually.
