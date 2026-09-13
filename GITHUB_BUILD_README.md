# ELIMIKA TIBA — Android APK Build

This project is prepared to build the ELIMIKA TIBA Android WebView app automatically with GitHub Actions.

## Build APK without Android Studio

1. Create a GitHub repository.
2. Upload ALL files and folders in this project.
3. Open the repository on GitHub.
4. Go to **Actions**.
5. Select **Build ELIMIKA TIBA APK**.
6. Click **Run workflow**.
7. Wait for the build to finish.
8. Open the completed workflow run.
9. Under **Artifacts**, download **ELIMIKA-TIBA-APK**.
10. Inside the downloaded artifact is `app-debug.apk`.

The APK is a debug APK intended for direct Android installation/testing.

## App

- App name: ELIMIKA TIBA
- Package: tz.co.elimika.tiba
- Website: https://tiba.elimika.co.tz/
- Android min SDK: 23
- Compile/Target SDK: 35
- WebView with JavaScript and DOM storage enabled
- Back button navigates WebView history
- HTTPS website loading
- Download support
- Camera permission support

## Important

The GitHub Actions workflow performs the Android build automatically. No Android Studio is required on your computer.
