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

### If you want a Afn Red Icon:
- Select Custom Branding Icon Afn Red
- Don't Select Custom Branding Icon Afn Blue
- Don't Select Custom Branding Icon Revancify

Using CLI: `-i custom-branding-icon-afn-red` `-e custom-branding-icon-afn-blue` `-e custom-branding-icon-revancify`

### If you want a Afn Blue Icon:
- Don't Select Custom Branding Icon Afn Red
- Select Custom Branding Icon Afn Blue
- Don't Select Custom Branding Icon Revancify

Using CLI: `-e custom-branding-icon-afn-red` `-i custom-branding-icon-afn-blue` `-e custom-branding-icon-revancify`

### If you want a Revancify Icon:
- Don't Select Custom Branding Icon Afn Red
- Don't Select Custom Branding Icon Afn Blue
- Select Custom Branding Icon Revancify

Using CLI: `-e custom-branding-icon-afn-red` `-e custom-branding-icon-afn-blue` `-i custom-branding-icon-revancify`

### If you want the Original YouTube Icon:
- Don't Select Custom Branding Icon Afn Red
- Don't Select Custom Branding Icon Afn Blue
- Don't Select Custom Branding Icon Revancify

Using CLI: `-e custom-branding-icon-red` `-e custom-branding-icon-blue` `-e custom-branding-icon-revancify`

### If you want a Custom App Name:
- Select Custom Branding Name

Using CLI: `-i custom-branding-name`

※ You can change the app name directly by opening `options.toml` in an editor. (Default: ReVanced Extended)

### If you want the Original YouTube App Name:
- Don't Select Custom Branding Name

Using CLI: `-e custom-branding-name`

### If you want Only Black Theme:
- Select Theme
- Don't Select Materialyou

Using CLI: `-i theme` `-e materialyou`

### If you want MaterialYou Theme (Only for Android 12+):
(Material Light Theme + Material Dark Theme)
- Don't Select Theme
- Select Materialyou

Using CLI: `-e theme` `-i materialyou`

### If you want MaterialYou Theme (Only for Android 12+) + Black Theme:
(Material Light Theme + Amoled Dark Theme)
- Select Theme
- Select Materialyou

Using CLI: `-i theme` `-i materialyou`

### If you don't want to make the player overlay button background color transparent:
- Don't Select Remove Player Button Background

Using CLI: `-e remove-player-button-background`

### If you want Force Premium Header:
- Select Force Premium Heading

Using CLI: `-i force-premium-heading`

※ Even if you do not select this patch option, you can toggle the Premium Header on/off in the Layout settings.

※ If you select this patch option, the Premium Header is enforced and the Premium Header toggle is removed from the Layout settings.
