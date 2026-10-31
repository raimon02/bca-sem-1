# BCA Study Sprint Android project

This Android Studio project wraps the self-contained BCA Study Sprint HTML app in an Android WebView. The app includes the daily motivational quote feature, unit check-offs, study-day rescheduling, revision prompts, and local progress backup/export.

## Build an APK

The easiest route is GitHub Actions:
1. Create a new GitHub repository and upload the contents of this folder.
2. Open the repository's **Actions** tab.
3. Select **Build Android APK** and click **Run workflow** (or push to `main`).
4. When the workflow finishes, open its run and download the `BCA-Study-Sprint-APK` artifact.
5. Extract `app-debug.apk` and install it on your Android phone. Android may ask you to allow installs from that source.

You can also open this folder in Android Studio and build via **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

Note: this environment does not include the Android SDK/build tools, so the APK itself could not be compiled here. The project and automated cloud-build workflow are included.
