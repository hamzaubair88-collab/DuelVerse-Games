# DuelVerse Games — Android starter project

This is an Android Studio project for an installable Android app. It packages a local HTML5 version of **Neon Racer: Escape** inside a native Android WebView, so the game runs offline and does not need a game website.

## Build an APK
1. Install Android Studio on a computer.
2. Open this `DuelVerseGames` folder in Android Studio.
3. Allow Gradle sync and install any requested Android SDK (compile SDK 35).
4. Choose **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. Android Studio will show the generated APK location. For Play Store publishing, create a signed Android App Bundle and complete the Play Console setup.

## Current prototype
- Game library home screen
- Neon Racer: Escape: three lanes, traffic, collectible energy orbs, nitro boost, three lives, score/distance, touch controls and keyboard controls
- Local assets only; no account or network permission required

## Next milestones
- Test on a real Android device and refine gameplay
- Add more original or properly licensed games
- Add persistent best scores, app icon, accessibility and release signing
- Prepare store listing, privacy details and publishing materials

This is source code, not a prebuilt or signed APK. Building and publishing require Android Studio and a developer account; publishing is not automatic.
