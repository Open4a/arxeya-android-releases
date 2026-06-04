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

## Current test release

Current debug updater release:

https://github.com/Open4a/arxeya-android-releases/releases/tag/android-v0.1.1-flow-ui-fix

Installed ARXEYA updater-capable builds read `app_latest.json` from this public repository and can guide future APK updates through Android's system installer.

Android still requires the user to confirm APK installation.
