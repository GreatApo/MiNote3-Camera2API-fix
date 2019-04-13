# MiNote3-Camera2API-fix
This is an TWRP flashable zip for Xiaomi Mi Note 3 intended to fix the Camera 2 API on MIUI10 8.1.

## Disclaimer
Use at your own risk. I am not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed.

## Instalation
0. Back up these files (or do a full backup):
- /system/etc/permissions/android.hardware.camera.full.xml
- /system/etc/permissions/android.hardware.camera.raw.xml
- /system/vendor/lib/libmmcamera_jason_s5k3p8sp_sunny.so
- /system/vendor/lib/hw/camera.sdm660.so
- /system/build.prop
1. Flash your new rom or update
2. Flash this zip form TWRP

## Problems
If sth doesn't work, restore your backuped files (do not forget to also add permitions) or dirty flash (flash over) your new rom or update from TWRP.

## Custom build.prop options
If you want to add some more options in your buid.prop, you can add them in file "/tmp/update-build.prop", and they will included in your buid.prop after flashing it.

## Credits
Camera fix: I was informed about this fix from [this xda topic](https://forum.xda-developers.com/mi-note-3/how-to/google-camera-how-to-mi-note-3-t3757049). All thanks go to: WebDingo, Savitar and also dianluitao, EnesSastim, dimi89
Buid.prop edit code: To edit the build.prop from within this flashable zip, the code from [this XDA post](https://forum.xda-developers.com/showpost.php?p=19093919&postcount=20) by unCoRrUpTeD was used.
