# E.I.S Messages — Releases

Official signed Android builds of **E.I.S Messages**, an SMS client for Android 8.0+.

This repository hosts release artifacts only. The source repository is private.

## Install

1. Download the APK from the [latest release](../../releases/latest).
2. Allow installation from your browser or file manager when prompted.
3. Open the APK and confirm the update. Release builds are signed with the same
   key, so they install over previous versions without losing app data.

## Verifying a download

Each release notes the APK version and signing certificate SHA-256 fingerprint.
Verify the file before installing:

```sh
apksigner verify --print-certs EIS-Messages-<version>.apk
sha256sum EIS-Messages-<version>.apk
```

## Support

E.I.S Messages is an independent project. Issues are tracked privately; report
problems through the contact listed on the release page.
