# NH House GOP app for Android

Release builds of the NH House GOP app (package `gop.nhhouse.whipcount`) for New Hampshire House Republican
caucus members whose phones don't use Google Play, such as de-Googled phones. This repo holds the installers
only. The source code is private.

You can't use the app without an account: registration sends a code to the email the caucus has on file for
you.

## Install with Obtainium (gets updates automatically)

1. In Obtainium, tap **Add App**.
2. Paste `https://github.com/cmaidmentnh/nh-house-gop-android` and tap **Add**.
3. Tap **Install**. Obtainium checks this page for new versions and offers each update.

## Install by hand

Download the `.apk` from the newest entry under [Releases](https://github.com/cmaidmentnh/nh-house-gop-android/releases),
open it on your phone, and allow the install if Android asks.

## First sign-in

Open the app, tap **Register** at the bottom of the sign-in screen, and enter your first and last name. Enter
the six-digit code from your email, then choose a username and password.

## Notes

- **Notifications:** push alerts need Google Play Services, so they won't arrive on a phone without it.
  Everything else works. New-survey alerts also come through the caucus Signal bot.
- **Pick one source:** a copy installed from Google Play and a copy installed from here may not update each
  other. If you switch, uninstall first.
- **Check the installer is genuine:** every release is signed with this certificate
  (SHA-256 `54295f7c98f040830d6ef3d6bb18ca0ae78900e95d6aa57f170df9052f72f225`,
  CN=NH House Republican Caucus). Obtainium and Android refuse an update signed by anything else.

Questions: reply to the caucus app email or contact your whip.
