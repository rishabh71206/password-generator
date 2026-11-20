# SecurePass Android App

Native Android wrapper (Kotlin + WebView) for the SecurePass password generator.
The website is bundled inside `app/src/main/assets/` so the app works **fully offline**.

## Build APK

1. Install [Android Studio](https://developer.android.com/studio)
2. Open the `android/` folder as a project
3. Let Gradle sync finish
4. Build → **Build APK(s)** → APK will be at:
   `app/build/outputs/apk/debug/app-debug.apk`

Install `app-debug.apk` on any Android phone (allow "install from unknown sources").

## Stack

- Kotlin (`MainActivity.kt`)
- Java 17, Android Gradle Plugin 8.5.2
- XML layouts & themes
- WebView loads `file:///android_asset/index.html`
