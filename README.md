# 🔐 SecurePass — Password Generator

A fast, animated password generator website + installable app.

## 🌐 Live Website

**https://rishabh71206.github.io/password-generator/**

## 📱 Features

- ✨ Smooth animations (gradient blobs, floating characters, scramble-reveal)
- 🎚️ Length slider (4–64) + Uppercase / Lowercase / Numbers / Symbols toggles
- 💪 Password strength meter (Weak → Unhackable)
- 📋 One-tap copy & regenerate
- 🗄️ **Built-in database** — save passwords with labels (stored locally)
- 📲 Installable as an app (PWA) on phone & PC — works offline

## 📦 Apps

| Platform | Type | Location |
|----------|------|----------|
| Web / PWA | Installable web app | Root folder (`index.html`) |
| Android | Native Kotlin app | `android/` folder |

## 🤖 Android APK

Open the `android/` folder in **Android Studio** → Build → Build APK(s).
See `android/README.md` for steps. The website is bundled inside the APK — works fully offline.

## 🛠️ Tech Stack

- HTML5, CSS3 (animations), Vanilla JavaScript
- `crypto.getRandomValues()` — cryptographically secure passwords
- localStorage database
- Kotlin + Java 17 + XML + Gradle (Android)
