# MiNote3-Camera2API-fix
This is an TWRP flashable zip for Xiaomi Mi Note 3 intended to fix the Camera 2 API on MIUI10 8.1 and MIUI10/11 9.0.

## Disclaimer
Use at your own risk. I am not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed.

## Features
MIUI10 Android 8.1 version
- Enables Camera2API in build.prop
- OIS/Front camera fixes (changes the appropriate lib files, credits at the bottom)

MIUI10/11 Android 9.0 version
(Combined by Engineer_Mode as Magisk module)
- Enables Camera2API in build.prop
- Enables EIS (Electronic image Stabilization) in build.prop
- Front Camera Fix
- TelePhoto Camera Packages List (Permissive Mode Needed)
- 1080p 120 fps Slow Motion in GCam
- Sound Stereo Record; HEVC Fix
- Additional Features Activated in Device Features

## Instalation
0. Back up these files (or do a full backup):

(On Android 8.1)
- /system/etc/permissions/android.hardware.camera.full.xml
- /system/etc/permissions/android.hardware.camera.raw.xml
- /system/vendor/lib/libmmcamera_jason_s5k3p8sp_sunny.so
- /system/vendor/lib/hw/camera.sdm660.so
- /system/build.prop

(On Android 9.0)
- /system/etc/device_features/jason.xml
- /system/priv-app/MiuiExtraPhoto/MiuiExtraPhoto.apk
- /system/priv-app/MiuiExtraPhoto/lib/arm64/libgallery_arcsoft_dualcam_refocus.so
- /system/priv-app/MiuiExtraPhoto/lib/arm64/libgallery_arcsoft_portrait_lighting.so
- /system/priv-app/MiuiExtraPhoto/lib/arm64/libgallery_arcsoft_portrait_lighting_c.so
- /system/priv-app/MiuiExtraPhoto/lib/arm64/libgallery_mpbase.so
- /system/priv-app/MiuiExtraPhoto/lib/arm64/libmibokeh_gallery.so
- /system/priv-app/MiuiExtraPhoto/lib/arm64/librefocus.so
- /system/priv-app/MiuiExtraPhoto/lib/arm64/librefocus_mibokeh.so
- /system/vendor/etc/media_codecs.xml
- /system/vendor/etc/media_codecs_performance.xml
- /system/vendor/etc/media_profiles.xml
- /system/vendor/etc/media_profiles_vendor.xml
- /system/vendor/etc/camera/jason_imx386_ofilm_chromatix.xml
- /system/vendor/etc/camera/jason_imx386_semco_chromatix.xml
- /system/vendor/etc/camera/jason_s5k3m3_ofilm_chromatix.xml
- /system/vendor/etc/camera/jason_s5k3m3_semco_chromatix.xml
- /system/vendor/etc/camera/jason_s5k3p8sp_sunny_chromatix.xml
- /system/vendor/etc/permissions/android.hardware.camera.ar.xml
- /system/vendor/etc/permissions/android.hardware.camera.flash-autofocus.xml
- /system/vendor/etc/permissions/android.hardware.camera.front.xml
- /system/vendor/etc/permissions/android.hardware.camera.full.xml
- /system/vendor/etc/permissions/android.hardware.camera.raw.xml
- /system/vendor/lib/libmmcamera_jason_s5k3p8sp_sunny.so
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
Latest versions for MIUI 10/11 are provided as magisk modules by [Engineer_Mode](http://4pda.ru/forum/index.php?showtopic=878111&st=3460#entry83639600)

Buid.prop edit code: To edit the build.prop, the code from [this XDA post](https://forum.xda-developers.com/showpost.php?p=19093919&postcount=20) by unCoRrUpTeD was used.

## I want more
A complete work/gather up about the GCam fixes for Mi Note 3 has been done by Engineer_Mode and you can learn more on [this 4PDA post](http://4pda.ru/forum/index.php?showtopic=878111&st=3460#entry83639600) (use Chrome's translate)
