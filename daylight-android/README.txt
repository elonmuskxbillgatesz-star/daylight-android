DAYLIGHT ANDROID APP — QUICK BUILD

This project packages your supplied Daylight HTML into an Android app using Capacitor.

FASTEST BUILD (cloud, no Android Studio required):
1. Sign in to GitHub and create a NEW repository named daylight-android.
2. Upload all files and folders from this ZIP into the repository (including the hidden .github folder).
3. Open the repository's Actions tab.
4. Select "Build Daylight APK" on the left, click "Run workflow", then click the green Run workflow button.
5. Wait for the workflow to finish successfully.
6. Open the completed run and download the "Daylight-APK" artifact.
7. Extract the downloaded ZIP; app-debug.apk is inside. Transfer it to your Android phone and install it.

NOTES:
- This is a debug APK for personal testing, not a Play Store release.
- The app's HTML is stored locally in www/index.html.
- The current HTML itself warns that browser-based reminders may not fire when the app is fully closed or the phone is locked. Packaging it as an APK does not automatically create reliable native alarms/notifications.
