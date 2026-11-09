FUTURE LIGHT SACCO - ANDROID PROJECT

What this is:
- Android Studio project for a standalone, offline-capable Android app.
- Member registration, savings, loans, repayments, member balances and CSV export.
- Loan interest is 10% ONCE on the original principal, not monthly.
- Records persist on the device using WebView local storage.

How to build the APK:
1. Install Android Studio on a Windows, Mac or Linux computer.
2. Extract this ZIP.
3. In Android Studio choose Open and select the FutureLightSACCO folder.
4. Allow Gradle sync and install the Android SDK platform requested (API 35).
5. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Android Studio will show the APK location, usually app/build/outputs/apk/debug/app-debug.apk.
7. Transfer that APK to your Android phone and install it. You may need to allow installation from that file manager.

Important:
- This environment does not have the Android SDK/Gradle build toolchain, so this ZIP is the Android Studio source project, not a compiled APK.
- Data is stored locally on the phone. Export CSV backups. Clearing app data or uninstalling can delete records.
- The app has no login, multi-device sync, server backup, audit trail, or role permissions yet. Add these before using it for important real SACCO funds.
