# YouFree Android build

This repository builds the upstream [LibreTube](https://github.com/libre-tube/LibreTube) Android app using GitHub Actions. The resulting APK is **LibreTube**, not a separately branded or audited YouFree fork.

## Build
Open **Actions → Build Android APK → Run workflow** (or push a commit). After a successful run, download the `android-debug-apk` artifact.

The workflow checks out the upstream source at build time. The upstream project is licensed under GPL-3.0; review its license, terms, and security before redistribution. Features may change and YouTube playback/ad filtering is not guaranteed.

This repository does not contain a prebuilt APK.