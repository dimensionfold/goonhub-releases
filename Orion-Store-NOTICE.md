# Orion Store attribution

Goonhub's expressive theme integration, press-feedback treatment, and self-update
state flow adapt patterns from Orion Store by RookieEnough / RookieZ.

- Upstream: https://github.com/RookieEnough/Orion-Store
- Reviewed revision: `79d67f7677d608f57bcdca7ec3df7b4807a29c48`
- Reference files: `ui/Theme.kt`, `ui/Common.kt`, `ui/StoreScreen.kt`,
  `ui/MainViewModel.kt`, and `platform/AppTracker.kt` under
  `app/src/main/java/com/orion/store/`.
- License: GNU GPL version 3; full text in `Orion-Store-GPL-3.0.txt`.

Goonhub modifications (2026): multiplatform motion bridge; existing user-selected
palettes, fonts, reduced motion and haptic intensity; TV press cancellation and
focus integration; optional, user-approved self-updates using Android
DownloadManager, APK verification and the system installer. Orion's branding,
catalog, forced-update gate, VirusTotal and privileged installers are not copied.

Goonhub remains under its existing AGPL-3.0 license. Orion-derived portions remain
covered by GPL-3.0, with combination permitted by section 13 of both licenses.
Corresponding source accompanies public APK releases.
