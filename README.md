# YT-Listener releases

Signed builds of the YT-Listener Android app, published here so the app can
update itself without a cable.

- `yt-listener.apk` is the current build.
- `version.json` is what the app reads to decide whether to download it.

The app checks periodically, and the top-bar menu has an item to check straight
away. It verifies the SHA-256 and the signing certificate before offering the
update, and Android asks you to confirm every install. Nothing here installs
silently.

Only this repository is public. The source stays private.
