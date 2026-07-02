# 3D Mate — Releases

Update feed and downloads for [3D Mate](https://3dmate.app), the native macOS
app for local, private AI image-to-3D generation.

- `appcast.xml` — Sparkle 2 update feed (the app checks this once a day).
- `updates/` — zipped, EdDSA-signed app builds.

The app source lives in a private repository; this repo only hosts what every
installed copy of the app downloads anyway. Updates are verified against the
public key embedded in the app before installing.
