# My One App — Android project

This is an Android Studio/Gradle project for the first installable **My One App** prototype.

## Build an APK using GitHub Actions (Android phone workflow)
1. Extract this ZIP on your Android phone.
2. Open GitHub in Chrome and create a new repository named `my-one-app`.
3. Upload the extracted project files and folders to the repository root (keep `.github/workflows/build-apk.yml`).
4. Commit the files to the `main` branch.
5. Open the repository's **Actions** tab.
6. Select **Build My One App APK** and choose **Run workflow** if it has not started automatically.
7. Wait for the workflow to finish successfully.
8. Open the completed workflow run, find **Artifacts**, and download `My-One-App-debug-APK`.
9. Extract the artifact ZIP to find `app-debug.apk`, then install it on your Android phone. Android may ask you to allow installation from your browser/files app.

## Current scope
- App label: My One App
- Package ID: `com.myoneapp.mobile`
- Android minimum SDK: 23
- The home screen and service tiles are a local UI prototype.
- All payment/transfer actions are demo-only. No live payment, wallet ledger, authentication backend, or provider API is connected.

## Before production
A production financial app needs a secure backend, real authentication, server-side transaction records, approved payment-provider integrations, fraud controls, privacy/security review, and relevant legal/regulatory approvals. Do not collect real customer credentials or accept real money in this prototype.

## Logo
The prototype uses a temporary original text mark. Add a logo only if you own it or have permission to use it.
