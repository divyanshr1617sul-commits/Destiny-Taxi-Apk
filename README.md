# Destiny Taxi — Android app

This is a native Android Studio project recreated from the supplied four-screen Destiny Taxi mockup.

## Included interaction flow
- Splash / Get Started
- Home dashboard
- Ride Now: pickup/drop-off + Mini/Sedan/SUV selection
- Driver On The Way: driver card, controls and fare details
- Tap targets move between the screens; the selected ride is highlighted.

## Build
Open this folder in Android Studio with an Android SDK installed, then choose **Build > Build APK(s)**.

Command-line build (with Gradle/Android SDK configured):

```bash
gradle :app:assembleDebug
```

APK output:
`app/build/outputs/apk/debug/app-debug.apk`

The current execution environment does not include the Android SDK/Gradle toolchain, so the APK itself could not be compiled here. The project is dependency-light and uses a single custom View, so it does not require external UI libraries.
