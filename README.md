# MiNote3-Camera2API-fix
This is an TWRP flashable zip for Xiaomi Mi Note 3 intended to fix the Camera 2 API on MIUI10 8.1 and MIUI10 9.0.

## Disclaimer
Use at your own risk. I am not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed.

## Features
MIUI10 8.1 version
- Enables Camera2API in build.prop
- OIS/Front camera fixes (changes the appropriate lib files, credits at the bottom)

MIUI10 9.0 version
- Enables Camera2API in build.prop
- Enables EIS (Electronic image Stabilization) in build.prop
- Front camera fixes (changes the appropriate lib files, credits at the bottom)
- OPTICAL IMAGE STABILIZATION SEEMS NOT TO WORK ON 9.0 WITH THIS FIX

## Instalation
0. Back up these files (or do a full backup):
- /system/etc/permissions/android.hardware.camera.full.xml
- /system/etc/permissions/android.hardware.camera.raw.xml
- /system/vendor/lib/libmmcamera_jason_s5k3p8sp_sunny.so
- /system/vendor/lib/hw/camera.sdm660.so	(only on 8.1)
- /system/build.prop
1. Flash your new rom or update
2. Boot to your system
3. Reboot into recovery
4. Make sure "System" is mounted (else mount it)
5. Flash this zip form TWRP

## Revert
If something doesn't work, restore your backuped files (do not forget to also add permissions) or dirty flash (flash over) your new rom/update from TWRP again.

## Custom build.prop options
If you want to add some more options in your buid.prop, you can add them in file "/tmp/update-build.prop", and they will be included in your buid.prop after flashing it.

## Credits
Camera fix: I was informed about this fix from [this XDA topic](https://forum.xda-developers.com/mi-note-3/how-to/google-camera-how-to-mi-note-3-t3757049). All thanks go to: WebDingo, Savitar and also dianluitao, EnesSastim, dimi89

Buid.prop edit code: To edit the build.prop, the code from [this XDA post](https://forum.xda-developers.com/showpost.php?p=19093919&postcount=20) by unCoRrUpTeD was used.

## I want more
A complete work/gather up about the GCam fixes for Mi Note 3 has been done by Engineer_Mode and you can learn more on [this 4PDA post](http://4pda.ru/forum/index.php?showtopic=878111&st=3460#entry83639600) (use Chrome's translate)
