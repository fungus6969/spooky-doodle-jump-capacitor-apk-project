# Spooky Doodle Jump — Capacitor APK Project

## Build Debug APK Locally
```bash
npm install
npx cap add android
npx cap sync android
cd android && ./gradlew assembleDebug
```

Your APK will be generated at:
`android/app/build/outputs/apk/debug/app-debug.apk`
