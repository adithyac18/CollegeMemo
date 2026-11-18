# College Memo (MIT Mysore) - Android app

Java + XML, Material Components, RecyclerView. Min SDK 24.

## Open in Android Studio
1. Clone / unzip this repo.
2. Android Studio > **File > Open** > select the `CollegeMemo` folder (the one that contains `settings.gradle`).
3. Wait for Gradle sync (needs internet the first time).
4. Run. Login with any non-empty username/password.

## Sync problems?
- Use a recent Android Studio (Koala / Ladybug or newer). Gradle JDK must be 17
  (Settings > Build, Execution, Deployment > Build Tools > Gradle > Gradle JDK > jbr-17 / "Embedded JDK").
- If asked to upgrade the Android Gradle Plugin, you can accept.
- File > Invalidate Caches > Invalidate and Restart, then sync again.

## Screens
Login > Home > Notices / Events (bottom nav: Home, Notifications, Profile).
