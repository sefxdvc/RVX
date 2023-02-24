Requirements (PC)
==
- ADB
- x86/x86_64 host architecture
- Zulu JDK 17

Common
==
### 0. If you are preparing to install in **ROOT environment**, follow the method below
- remove all YouTube related modules
- remove directories: `/data/adb/service.d`, `/data/adb/post-fs-data.d`, `/data/adb/revanced`
- reboot device

​
### 1. Check the [README.md](https://github.com/inotia00/revanced-patches/tree/revanced-extended#-json-format) of revanced-patches for supported YouTube versions

![compatible](https://user-images.githubusercontent.com/108592928/221310639-6bfd8d2c-ea9c-41af-b0c2-59ba1560fa3b.png)

※ For YouTube Music, all versions are supported
​

### 2. Download the supported version of YouTube / YouTube Music from APKMirror and **_install it on your device._**

![ReVanced_Manager3](https://user-images.githubusercontent.com/108592928/221310762-f85a6109-3246-4a4f-9c2b-04d0922238c6.png)

※ You must download the `nodpi` version.

### 3. Extra: Include / Exclude patches
- You can include or exclude all patches, except the ones below (The following patches must be included)

: `patch-options`

- Read [this document](https://github.com/inotia00/revanced-documentation/wiki/Options-Information-about-the-patch) for a list of patches you can include or exclude.