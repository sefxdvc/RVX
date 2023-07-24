Information
==
### 1. This document is a guide on how to build ReVanced Extended using the RVX Manager.
### 2. To use the RVX Manager, the following conditions must be met:
- Your device must use the arm64-v8a architecture.
- Your device must be running Android 8.0+

Common
==
### 0. If you are preparing to install in **ROOT environment**, follow the method below
- remove all YouTube related modules
- remove directories: `/data/adb/service.d`, `/data/adb/post-fs-data.d`, `/data/adb/revanced`
- reboot device

​
### 1. Check the [README.md](https://github.com/inotia00/revanced-patches/tree/revanced-extended#-json-format) of revanced-patches for supported YouTube versions

![support_version](https://github.com/inotia00/revanced-documentation/assets/108592928/8b0cf17d-e536-414e-923a-5c37fdc309dd)

※ For YouTube Music, all versions are supported
​

### 2. Download the supported version of YouTube / YouTube Music from APKMirror and **_install it on your device._**

![apkmirror](https://github.com/inotia00/revanced-documentation/assets/108592928/f0bc6720-3c37-41b0-a689-216dd38cea8d)

※ You must download the `nodpi` version.


### 3. Download [RVX Manager](https://github.com/inotia00/revanced-manager/releases/latest) from the github and install it on your device

### 4. Launch RVX Manager and click `Select an application`.

![1](https://github.com/inotia00/revanced-documentation/assets/108592928/22ca109b-abd6-4d1a-95e9-1576c0bcb205)

### 5. Click the `Storage` button and select the YouTube APK that you downloaded from APKMirror

![2](https://github.com/inotia00/revanced-documentation/assets/108592928/2ff47b47-a3af-424b-ae53-69377d2ee5d1)

### 6. Click `Selected patches` and include or exclude the patches you want

![3](https://github.com/inotia00/revanced-documentation/assets/108592928/06d1567f-55a4-420a-9818-877f7339e141)

- If you don't know what to decide, just click the `Default` button

- When selected, click the `Done` button


※ Read [this document](https://github.com/inotia00/revanced-documentation/wiki/Options-Information-about-the-patch) for a list of patches you can include or exclude.
※ Read [this document](https://github.com/ReVanced-Extended-Community/Patches-Documentation) to see a screenshot of each patch


NON-ROOT environment
==
When patching, please **include** the following patches

- **`MicroG Support`**


ROOT environment
==
When patching, please **exclude** the following patches

- **`MicroG Support`**


I recommend installing the [Detach Magisk module](https://forum.xda-developers.com/t/module-detach3-detach-market-links.3447494/) after patching.

※ [Detach Magisk module](https://forum.xda-developers.com/t/module-detach3-detach-market-links.3447494/) prevents automatic updates by Google Playstore. (Prevent crashes from occurring in the ROOT environment)