# Intraday Position Size Calculator — Android project

This is a native Android shell with an offline WebView calculator embedded in app assets.

## Features
- Capital input (default ₹2,00,000)
- Entry and stop-loss price inputs
- Buy/Long and Sell/Short direction validation
- Risk fixed at 1% of capital
- Maximum leverage capped at 5x
- Quantity rounded down to whole shares and capped by risk and leverage
- Position value, estimated margin, and estimated stop-loss risk
- 1.5R and 2R target prices and profit estimates
- Estimated 70% booked profit / 30% runner split
- Offline use; no network permission
- Launcher icon

## Build APK
1. Install Android Studio (current stable) on a computer.
2. Open this folder as a project.
3. Allow Gradle sync and install Android SDK Platform 35 if prompted.
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Find the debug APK under `app/build/outputs/apk/debug/app-debug.apk`.
6. Transfer the APK to your Android phone and install it. If prompted, allow installing unknown apps for the file manager used.

This source package was generated in an environment without Android SDK/Gradle build tools, so an APK could not be compiled here.
