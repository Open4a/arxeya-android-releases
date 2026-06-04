# ARXEYA Android Releases

Public Android release artifacts for ARXEYA.

Development source stays private in `Open4a/arxeya`.

This public repository may contain only safe distribution files:

- APK release assets;
- `app_latest.json`;
- `content_manifest.json`;
- install notes;
- checksums.

Do not publish source code, `local.properties`, keystores, secrets, private configs, or local build folders here.

## First updater MVP

Phones with an older ARXEYA build that does not contain updater code cannot update themselves.
Install the first updater-capable APK manually once from the GitHub Release:

https://github.com/Open4a/arxeya-android-releases/releases/tag/android-v0.1.0-updater-mvp

After this updater-capable APK is installed, ARXEYA can check public manifests at startup and guide future APK updates through Android's system installer.

Android still requires the user to confirm APK installation.
