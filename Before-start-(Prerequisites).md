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

![compatible](https://user-images.githubusercontent.com/108592928/220423797-b787341d-89e8-4613-b402-02f15b6e7e9f.png)

※ For YouTube Music, all versions are supported
​

### 2. Download the supported version of YouTube / YouTube Music from APKMirror and **_install it on your device._**

![ReVanced_Manager2](https://user-images.githubusercontent.com/108592928/220423945-219fd2d1-59ff-4420-9a05-dd7a8760ee1d.png)

※ You must download the `nodpi` version.

### 3. Extra: Include / Exclude patches
- You can include or exclude all patches, except the ones below (The following patches must be included)

: `patch-options`

- Read [this document](https://github.com/inotia00/revanced-documentation/wiki/Options-Information-about-the-patch) for a list of patches you can include or exclude.