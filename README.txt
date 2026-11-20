Operation Death (عملیات مرگ) — Android project
Made by: ALI VIP

How to build the APK (Android Studio):
1. Install Android Studio (https://developer.android.com/studio).
2. File > Open > select this "OperationDeath" folder. Wait for Gradle sync to finish
   (the first sync needs internet to download Gradle + libraries).
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. The APK will be at: app/build/outputs/apk/debug/app-debug.apk  -> copy it to your phone and install.

Notes:
- The game file lives at app/src/main/assets/www/index.html. To update the game, replace that file and rebuild.
- The Back button sends "Esc" to the game (pause). Press Back twice quickly to exit.
- INTERNET permission is only used to load the Vazirmatn font from Google Fonts; offline, the system font is used.
