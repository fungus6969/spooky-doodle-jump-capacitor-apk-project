# Spooky Doodle Jump — Android Studio & Gradle APK Project

Package ID: `com.spookyarcade.doodlejump`
Version: `1.0.0` (`versionCode 1`)
Target SDK: `35` | Min SDK: `24`

## Option 1: Build APK with Android Studio
1. Extract this ZIP archive.
2. Open the extracted folder in **Android Studio**.
3. Wait for Gradle Sync to finish.
4. Click **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

## Option 2: Build APK via GitHub Actions (No Local Android Studio Needed)
1. Push this extracted folder to a GitHub repository.
2. Open the **Actions** tab and run **Build Android APK** (or push to `main`).
3. Download `spooky-doodle-jump-debug-apk` containing `app-debug.apk` and install on your Android phone.

## Option 3: Command Line (with Gradle + Android SDK installed)
```bash
gradle assembleDebug
```
Output APK: `app/build/outputs/apk/debug/app-debug.apk`
