Options: Information about the patch
==
### [YouTube](https://github.com/inotia00/revanced-patches/tree/revanced-extended#-comgoogleandroidyoutube)

### [YouTube Music](https://github.com/inotia00/revanced-patches/tree/revanced-extended#-comgoogleandroidappsyoutubemusic)

Patches that need to be included or excluded depending on the situation
==

### If you want the ROOT version:
- Don't Select MicroG Support
- Don't Select Custom Package Name

Using CLI: `-e microg-support`

### If you want a Revancify Red Icon:
- Don't Select Custom Branding Icon MMT
- Select Custom Branding Icon Revancify Red
- Don't Select Custom Branding Icon Revancify Blue

Using CLI: `-e custom-branding-icon-mmt` `-i custom-branding-icon-revancify-red` `-e custom-branding-icon-revancify-blue`

### If you want a Revancify Blue Icon:
- Don't Select Custom Branding Icon MMT
- Don't Select Custom Branding Icon Revancify Red
- Select Custom Branding Icon Revancify Blue

Using CLI: `-e custom-branding-icon-mmt` `-e custom-branding-icon-revancify-red` `-i custom-branding-icon-revancify-blue`

### If you want a MMT Icon:
- Select Custom Branding Icon MMT
- Don't Select Custom Branding Icon Revancify Red
- Don't Select Custom Branding Icon Revancify Blue

Using CLI: `-i custom-branding-icon-mmt` `-e custom-branding-icon-revancify-red` `-e custom-branding-icon-revancify-blue`

### If you want the Original YouTube Icon:
- Don't Select Custom Branding Icon MMT
- Don't Select Custom Branding Icon Revancify Red
- Don't Select Custom Branding Icon Revancify Blue

Using CLI: `-e custom-branding-icon-mmt` `-e custom-branding-icon-revancify-red` `-e custom-branding-icon-revancify-blue`

### If you want a Custom App Name:
- Select Custom Branding YouTube Name / Custom Branding Music Name

Using CLI: `-i custom-branding-youtube-name` `-i custom-branding-music-name`

※ You can change the app name directly by opening `options.toml` in an editor. (Default: ReVanced Extended)

### If you want the Original App Name:
- Don't Select Custom Branding YouTube Name / Custom Branding Music Name

Using CLI: `-e custom-branding-youtube-name` `-e custom-branding-music-name`

### If you want Stock YouTube Theme:
- Don't Select Theme
- Don't Select Materialyou

Using CLI: `-e theme` `-e materialyou`


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

### If you want Force Premium Header:
- Select Force Premium Heading

Using CLI: `-i force-premium-heading`

※ Even if you do not select this patch option, you can toggle the Premium Header on/off in the Layout settings.

※ If you select this patch option, the Premium Header is enforced and the Premium Header toggle is removed from the Layout settings.
