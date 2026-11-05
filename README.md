# Bilal Collection Android App

Android inventory and sales app project for Bilal Collection.

## Build APK in GitHub Actions (no computer needed)
1. Create a public or private GitHub repository named `BilalCollection`.
2. Upload the contents of this folder to the repository root (the `app`, `.github`, and Gradle files; do not upload the outer folder itself).
3. Open the repository's **Actions** tab and select **Build Bilal Collection APK**.
4. Tap **Run workflow**. Wait for the run to finish successfully.
5. Open the completed run, find **Artifacts**, and download `Bilal-Collection-debug-apk`.
6. Extract the downloaded artifact ZIP; install `app-debug.apk` on your Android phone. Only install APKs you built from this repository.

The APK is a debug build for testing, not a Play Store release.
