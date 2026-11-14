# Custom Dino Runner (Android)

Your Dino Dash game wrapped as an Android app named "Custom Dino Runner".

## Easiest: build the APK online (no Android Studio)
1. Create a free account at github.com and make a new repository.
2. Upload everything in this folder (keep the .github folder).
3. Open the Actions tab, run "Build Custom Dino Runner APK" (it also runs on every upload).
4. When it finishes (about 5 minutes), open the run and download "Custom-Dino-Runner-APK".
5. Unzip it, copy "Custom Dino Runner.apk" to your phone, tap it, and allow "Install unknown apps".

## Alternative: Android Studio
1. Install Android Studio, choose Open, and select the android folder.
2. Build > Build APK(s). The file is in android/app/build/outputs/apk/debug/.

To change the game, edit www/index.html, then run: npx cap sync android
