Common
==
### 0. If you are preparing to install in **ROOT environment**, follow the method below
- remove all YouTube related modules
- remove directories: `/data/adb/service.d`, `/data/adb/post-fs-data.d`, `/data/adb/revanced`
- reboot device

​
### 1. Check the [README.md](https://github.com/inotia00/revanced-patches/tree/revanced-extended#-json-format) of revanced-patches for supported YouTube versions

![ReVanced_Manager1](https://user-images.githubusercontent.com/108592928/202146941-ed3575a3-30d5-49a8-9f55-ff141a7c5f5b.png)

※ For YouTube Music, all versions are supported
​

### 2. Download the supported version of YouTube / YouTube Music from APKMirror and **_install it on your device._**

![ReVanced_Manager2](https://user-images.githubusercontent.com/108592928/202147431-37ef69d0-4688-40c5-8280-0563ae27fdee.png)

※ You must download the `nodpi` version.

### 3. Extra: Include / Exclude patches
- I recommend including all, except for some patches.

- Because ReVanced Extended is designed assuming all patches are included.

- Also, since my patch does not support `settings-framework`, excluding the patch will not remove it from the Settings UI.

- Read [this document](https://github.com/inotia00/revanced-documentation/wiki/Options-Information-about-the-patch) for a list of patches you can include or exclude.


Using RVX Builder (Windows / MacOS / Linux)
==
- Download the rvx-builder from [Latest releases](https://github.com/inotia00/rvx-builder/releases/latest), and Run

※ For most rvx-builder errors (PC environment), please refer to [this issue pages](https://github.com/inotia00/rvx-builder/issues/7)

Using RVX Builder (Android - termux)
==
- [How to use rvx builder on Android](https://github.com/inotia00/rvx-builder/wiki/How-to-use-rvx-builder-on-Android)