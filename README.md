# MiNote3-Camera2API-fix
This is an TWRP flashable zip for Xiaomi Mi Note 3 intended to fix the Camera 2 API on MIUI10 8.1 and MIUI10/11/12 9.0.

## Disclaimer
Use at your own risk. I am not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed.

## Features
MIUI10 Android 8.1 version
- Enables Camera2API in build.prop
- OIS/Front camera fixes (changes the appropriate lib files, credits at the bottom)

MIUI10/11/12 Android 9.0 version
(Combined by Engineer_Mode as Magisk module)
- Enables Camera2API in build.prop
- Enables EIS (Electronic image Stabilization) in build.prop
- Front Camera Fix
- TelePhoto Camera Packages List (Permissive Mode Needed)
- 1080p 120 fps Slow Motion in GCam
- Sound Stereo Record; HEVC Fix
- Additional Features Activated in Device Features

## Installation
0. Back up /system/ files (or do a full backup)
1. Flash your new ROM or update
2. Boot to your system
3. Reboot into recovery
4. Flash this zip form TWRP

## Revert
If something doesn't work, restore your backup files (do not forget to also add permissions) or dirty flash (flash over) your new ROM/update from TWRP again.

## Custom build.prop options
If you want to add some more options in your buid.prop, you can add them in file "/tmp/update-build.prop", and they will be included in your buid.prop after flashing it.

## Credits
Camera fix: I was informed about this fix from [this XDA topic](https://forum.xda-developers.com/mi-note-3/how-to/google-camera-how-to-mi-note-3-t3757049). All thanks go to: WebDingo, Savitar and also dianluitao, EnesSastim, dimi89
Latest versions for MIUI 10/11 are provided as magisk modules by [Engineer_Mode](http://4pda.ru/forum/index.php?showtopic=878111&st=3460#entry83639600)

Buid.prop edit code: To edit the build.prop, the code from [this XDA post](https://forum.xda-developers.com/showpost.php?p=19093919&postcount=20) by unCoRrUpTeD was used.

## I want more
A complete work/gather up about the GCam fixes for Mi Note 3 has been done by Engineer_Mode and you can learn more on [this 4PDA post](http://4pda.ru/forum/index.php?showtopic=878111&st=3460#entry83639600) (use Chrome's translate)
