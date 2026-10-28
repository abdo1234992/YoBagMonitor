# YO Bag Monitor — Notification prototype 0.2.0

Android Studio project. Monitors newly posted notifications from `com.weifan.yo` after the user explicitly enables Notification Access in Android Settings.

## Build
1. Open this folder in Android Studio.
2. Sync Gradle.
3. Build > Build APK(s).
4. Install the debug APK.
5. Open the app, tap **Open notification access settings**, and enable YO Bag Monitor.
6. Wait for a new Wanasa notification, then return and tap **Refresh list**.

## Limitations
- Captures only notification title/text exposed by Android; it cannot infer bag details if Wanasa's notification is generic.
- Records are in memory only and disappear when the process is killed.
- No Root, Accessibility Service, Xposed, login/session extraction, external server, or automatic claiming.
