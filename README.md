# Earth Bingo Android Project

This project wraps the provided Earth Bingo HTML/CSS/JavaScript in an Android WebView and exposes Android Text-to-Speech as `AndroidVoice.speak(...)`.

## Build
Open this folder in Android Studio and build `app` -> `assembleDebug`. The debug APK will be at:
`app/build/outputs/apk/debug/app-debug.apk`

A GitHub Actions workflow is included at `.github/workflows/build-apk.yml` for cloud builds. For GitHub Actions, ensure a Gradle wrapper (`gradlew`, `gradlew.bat`, and `gradle/wrapper/`) is added to the repository; the workflow falls back to system Gradle, which may not be available on all runners.

The wallet and prize values are demo-only and are not connected to real money.
