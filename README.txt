URJVANTA SOLAR ENERGY — ANDROID STUDIO PROJECT

This is an Android Studio source project wrapping the existing solar information website in an Android WebView.
It is NOT a compiled APK yet.

Features in the app:
- Solar Calculator (rough estimate only)
- Solar Water Pump information
- On-grid vs Hybrid / battery backup information
- Solar quote enquiry form that opens WhatsApp
- Call and WhatsApp contact buttons for 7410727355

Build an APK:
1. Install Android Studio on a computer.
2. Open the folder named UrjvantaSolarAndroid (the folder containing settings.gradle).
3. Let Android Studio sync Gradle and install Android SDK Platform 35 if prompted.
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. The debug APK will usually be at app/build/outputs/apk/debug/app-debug.apk.

Notes:
- Internet is not needed for the core screens; WhatsApp and calling need the relevant phone apps/network.
- Solar sizing results are preliminary estimates, not a professional design or quotation.
- Before public release, test on multiple Android phones and add a privacy policy if collecting customer information.
