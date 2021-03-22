<p align="center">
  <img src="https://raw.githubusercontent.com/Magisk-Modules-Repo/Pix3lify/master/.github/logo.png">
</p>

<p align="center">
 <a href="https://forum.xda-developers.com/apps/magisk/module-pixel-2-experience-t3757137"><img src="https://img.shields.io/badge/XDA-Thread-orange.svg"></a><br /><a href="https://t.me/PIX3LIFY"><img src="https://img.shields.io/badge/Telegram-Group-blue.svg"></a><br /><a href="https://discord.gg/sUyZdSv"><img src="https://img.shields.io/discord/529370157563510814.svg"></a>
</p>

## ⭐ Module description

As a Non Pixel user, I was stuck with Stock Oreo 8.0.0 without Oreo custom ROMs when I first bought my device. Kernel sources weren't released at the time so I decided if I can cook up a Magisk module that can bring me the Pixel UI without the need to install that ROM. What I did is to search around the internet which lead me to download the Pixel 3 XL factory images and extract the files mostly needed in the new Pixel 3 devices. I've decided to gather these files and compiled them all into a single Magisk Module. This module can be flashed with other devices on Oreo and above as well.

## ⭐ Compatibility

-   [![Magisk](https://img.shields.io/badge/Magisk-18%2B-00B39B.svg)](https://forum.xda-developers.com/apps/magisk/official-magisk-v7-universal-systemless-t3473445)
-   [![Android Oreo+](https://img.shields.io/badge/Oreo-8.0+-blue.svg)](https://www.android.com/versions/oreo-8-0/)
-   Close to Stock/AOSP ROMs (not for MIUI, TouchWiz, EMUI, OOS, etc.)
-   All root solutions (requires init.d support if not using Magisk or supersu. Try [Init.d Injector](https://forum.xda-developers.com/android/software-hacking/mod-universal-init-d-injector-wip-t3692105))
-   Pixel, Nexus, and OxygenOS devices are not compatible and were leading to bootloops. The module will now warn about this and give the option to abort or bypass warning and install anyway(to uninstall if in bootloop, boot to twrp and flash zip).

## ⭐ Reminders

-   TO COMPLETELY UNINSTALL THE MODULE AND AVOID BOOTLOOPS, INSTALL THE ZIP AGAIN IN MAGISK OR TWRP!!
-   Take a full backup before installing the module.
-   Please send Pix3lify debug file from internal storage or logcat if any issues/bugs occur.

## ⭐ Users without working volume keys

-   To choose options without using volume keys, you can rename the zip
-   Currently the choices are FULL, SLIM, OVER, ACC, BOOT, FONT, WCRG, and EMJI.
-   FULL = The full module not including overlay/accent and boot animation
-   SLIM = No additional apps, wellbeing scripts, fonts, sounds, and all overlays except pix3lify.
-   OVER = Install pixel framework changes ( a lot of the main features is in this, inc. Night Light)
-   ACC = Install pixel accent
-   BOOT = Install pixel boot animation
-   FONT = **Replace** stock font with Product Sans ( IF U HAVE LOCKSCREEN ISSUES TURN OFF IT WILL STILL ADD THE SANS FONTS )
-   WCRG = Add Pixel Stand feature and app
-   EMJI = Uses Android Q’s new Emoji set (following Google’s Oreo Emoji theme)
-   To use the basename zip feature all you need to do is add the options to the zipname and only flash the zip in recovery. Magisk renames all zips to install.zip so flashing in magisk manager will NOT work. Heres an example of using basename to install full and overlays ( Pix3lify-2.6-full-over.zip )
-   The options can either be full, Full, or FULL ( applies to all options )

## ⭐ Features

-   Pixel Blue theme accent
-   Adds Daydream VR support
-   Adds Digital Wellbeing in Settings app
-   Adds Gestures in Settings app (device dependent)
-   Adds Pixel alarms/media/ringtones/UI sounds
-   Adds Pixel Stand app (wireless charging stand)
-   Adds Pixel Sounds app ([mileage may vary](https://github.com/Magisk-Modules-Repo/Pix3lify/wiki/Sounds))
-   Adds Google Markup app (Android 5+)
-   Adds Pixel exclusive wallpapers
-   Enables Nexus, Pixel, and Android One app support
-   Enables Google Dialer install via Playstore
-   Enables Google Dialer's Call Screening ([mileage may vary](https://github.com/Magisk-Modules-Repo/Pix3lify/wiki/Call-Screening))
-   Enables Camera2 API support (find a working Modded Google Camera app [here](https://www.celsoazevedo.com/files/android/google-camera/))
-   Enables EIS support (device dependent)
-   Enables Google Assistant
-   Enables Night Light (device dependent)
-   Uses ystem-wide or header Product Sans
-   Uses emoji from Android Q

## ⭐ Changelog
### v3.0.4
-   Emoji from Android Q option



### v2.9.1

-   Fix hanging in terminal script
-   Detect if dialer is installed
-   Fix find command
-   Remove autoDND/flip to shhh
-   Fix Wellbeing
-   Bug fixes
-   Unity update
-   Add font option



### v2.1

-   Hot Fixes

### v2.0

-   BIG UPDATE!
-   Add more fonts
-   Update Unity fixes
-   Introduce logging
-   Add pix3lify terminal script to send logs
-   Bug fixes/typos
-   Unity 3.3
-   Added xmlstarlet for xml patching
-   Bug fixes/typos
-   Add (FULL) or (SLIM) to module.prop depending on user choice
-   Magisk backwards compatibility



## ⭐ Contributors

-   **Pika**, for code reviews and support
-   **JohnFawkes**, for debugging help
-   **thehappydinoa**, for the Google Call Screening and Flip to Shhh
-   **Laster K.**, for Night Light fixes and Daydream VR additions
-   **Skittles9823**, for helping me rename the module

## ⭐ Thanks!

-   Thanks to @Didgeridoohan for his magisk hide props config logging code
-   Thanks to @veez21 for his mod-util terminal script template
-   Thanks to @TadiT7 for xmlpak
-   Thanks to @zackptg5 for Unity and cleaning up our code
-   Thanks to @TopJohnWu for Magisk

## ⭐ Links

-   [![LICENSE](https://img.shields.io/github/license/Magisk-Modules-Repo/Pix3lify.svg)](https://github.com/Soumendu69/web/blob/main/LICENSE)
-   [![Pix3lify XDA Portal feature](https://img.shields.io/badge/XDA-Portal-orange.svg)](https://www.xda-developers.com/pixel-2-experience-magisk-module/)
-   [![Source Code](https://img.shields.io/badge/Github-Source-black.svg)](https://github.com/Magisk-Modules-Repo/Pix3lify)
