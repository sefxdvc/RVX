Options: Information about the patch
==
### [YouTube](https://github.com/inotia00/revanced-patches/tree/revanced-extended#-comgoogleandroidyoutube)

### [YouTube Music](https://github.com/inotia00/revanced-patches/tree/revanced-extended#-comgoogleandroidappsyoutubemusic)

Patches that need to be included or excluded depending on the situation
==

### If you want the ROOT version:
- Don't Select MicroG Support
- Don't Select Custom Package Name

Using CLI: `-e microg-support -e custom-package-name`(YouTube) or `-e music-microg-support -e custom-package-name-music`(YouTube Music)

### If you want a Custom Package Name:
- Select Custom Package Name

Using CLI: `-i custom-package-name`(YouTube) or `-i custom-package-name-music`(YouTube Music)

※ This patch option is for users who want to use the official ReVanced and ReVanced Extended at the same time.

※ Caution: Be sure to include only **NON-ROOT** users.

### If you want a ReVanced Red Icon:
- Select Custom Branding Icon Red
- Don't Select Custom Branding Icon Blue
- Don't Select Custom Branding Icon Revancify

Using CLI: `-i custom-branding-icon-red` `-e custom-branding-icon-blue` `-e custom-branding-icon-revancify`

### If you want a ReVanced Blue Icon:
- Don't Select Custom Branding Icon Red
- Select Custom Branding Icon Blue
- Don't Select Custom Branding Icon Revancify

Using CLI: `-e custom-branding-icon-red` `-i custom-branding-icon-blue` `-e custom-branding-icon-revancify`

### If you want a Revancify Icon:
- Don't Select Custom Branding Icon Red
- Don't Select Custom Branding Icon Blue
- Select Custom Branding Icon Revancify

Using CLI: `-e custom-branding-icon-red` `-e custom-branding-icon-blue` `-i custom-branding-icon-revancify`

### If you want the Original YouTube Icon:
- Don't Select Custom Branding Icon Red
- Don't Select Custom Branding Icon Blue
- Don't Select Custom Branding Icon Revancify

Using CLI: `-e custom-branding-icon-red` `-e custom-branding-icon-blue` `-e custom-branding-icon-revancify`

### If you want a Custom App Name:
- Select Custom Branding Name

Using CLI: `-i custom-branding-name`

※ You can change the app name directly by opening `options.toml` in an editor. (Default: ReVanced Extended)

### If you want the Original YouTube App Name:
- Don't Select Custom Branding Name

Using CLI: `-e custom-branding-name`

### If you want Black Theme:
- Select Amoled
- Don't Select Materialyou

Using CLI: `-i amoled` `-e materialyou`

### If you want MaterialYou Theme (Only for Android 12+):
- Select Amoled
- Select Materialyou

Using CLI: `-i amoled` `-i materialyou`

### If you want Force Premium Header:
- Select Premium Heading

Using CLI: `-i premium-heading`

※ Even if you do not select this patch option, you can toggle the Premium Header on/off in the Extended settings.

※ If you select this patch option, the Premium Header is enforced and the Premium Header toggle is removed from the Extended settings.

### If you don't want Website:
- Don't Select Website

Using CLI: `-e website`(YouTube) or `-e website-music`(YouTube Music)
