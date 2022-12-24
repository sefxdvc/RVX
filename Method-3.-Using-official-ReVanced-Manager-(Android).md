Information
==
### 1. This document is a guide on how to build ReVanced Extended using the official ReVanced Manager.
### 2. To use the official ReVanced Manager, the following conditions must be met:
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

![compatible](https://user-images.githubusercontent.com/108592928/209435297-fef7955b-db7e-4e16-80b7-23cee48a0754.png)

※ For YouTube Music, all versions are supported
​

### 2. Download the supported version of YouTube / YouTube Music from APKMirror and **_install it on your device._**

![ReVanced_Manager2](https://user-images.githubusercontent.com/108592928/202147431-37ef69d0-4688-40c5-8280-0563ae27fdee.png)

※ You must download the `nodpi` version.

### 3. Download [ReVanced Manager](https://github.com/revanced/revanced-manager/releases/latest) from the official repo and install it on your device

※ Even if ReVanced Manager is already installed on the device, I recommend reinstalling it.

### 4. Launch ReVanced Manager and go to settings.

### 5. Select `Sources`, change as follows, and **restart ReVanced Manager**

![ReVanced_Manager3](https://user-images.githubusercontent.com/108592928/202158656-525286ae-7a18-408f-a2d9-cc97bc5668e1.png)

### 6. Follow the screenshots to proceed with the patch.

![ReVanced_Manager4](https://user-images.githubusercontent.com/108592928/202160529-5a62e8ed-40c6-444f-9ad9-447868a29396.png)

![ReVanced_Manager5](https://user-images.githubusercontent.com/108592928/202160603-00138b03-821a-4ca8-b83a-57accc054f31.png)

※ I recommend including all, except for some patches.

※ Because ReVanced Extended is designed assuming all patches are included.

※ Also, since my patch does not support `settings-framework`, excluding the patch will not remove it from the Settings UI.

※ Read [this document](https://github.com/inotia00/revanced-documentation/wiki/Options-Information-about-the-patch) for a list of patches you can include or exclude.

NON-ROOT environment
==
When patching, please **include** the following patches

- **`MicroG Support`** (YouTube)

- **`Music MicroG Support`** (YouTube Music)


ROOT environment
==
When patching, please **exclude** the following patches

- **`MicroG Support`** (YouTube)

- **`Music MicroG Support`** (YouTube Music)

I recommend installing the [Detach Magsik module](https://forum.xda-developers.com/t/module-detach3-detach-market-links.3447494/) after patching.

※ [Detach Magsik module](https://forum.xda-developers.com/t/module-detach3-detach-market-links.3447494/) prevents automatic updates by Google Playstore. (Prevent crashes from occurring in the ROOT environment)