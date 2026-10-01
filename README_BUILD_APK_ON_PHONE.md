# FOXX Social Network — Complete Android Studio Project (Kotlin + Jetpack Compose)

Package Name: com.foxx.social
Min SDK: 24 (Android 7.0+) | Target & Compile SDK: 35 (Android 15)
Firebase Project: gen-lang-client-0268928790
Firestore Database ID: ai-studio-dad928a0-e6f5-4274-949e-68ba59b0ff3b

## How to Build the APK on an Android Phone WITHOUT a PC

### Method 1: Free Cloud Build via GitHub Actions (Recommended on Android Phone)
1. Open Chrome on your Android phone and sign in to https://github.com.
2. Create a new repository (e.g. `foxx-android-apk`).
3. Upload the files from this ZIP (or click "Export to GitHub" directly in the Google AI Studio top bar).
4. Tap the **Actions** tab in your GitHub repository.
5. Select **Build FOXX Android APK (Cloud Builder — No PC Needed)** and tap **Run workflow**.
6. In ~2 minutes, tap the completed workflow run and download **FOXX-Android-APK.zip**, extract `app-debug.apk`, and tap it on your Android phone to install FOXX!

### Method 2: On-Device Local Build using AndroidIDE (No PC Required)
1. Install **AndroidIDE** (from https://androidide.com or F-Droid) on your Android phone.
2. Extract this downloaded `FOXX-Android-Studio-Project.zip` into `/storage/emulated/0/AndroidIDEProjects/FOXX`.
3. Open the folder in AndroidIDE, wait for Gradle sync to complete, and tap the **Run / Build APK** play button at the top.
4. AndroidIDE will compile `app-debug.apk` and prompt you to install it directly on your phone.
