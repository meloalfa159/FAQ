# Meloalfa159 FAQ

Here is most asked questions and respective answers. 

## Which recovery should I use?

The answer is [orangefox recovery](https://t.me/melo159roms/177). But **important**: if you just unlocked your bootloader and/or have stock miui recovery, you need to flash TWRP first, because you need to flash it by fastboot having it as an image (`fastboot flash recovery path/to/TWRP.img`). After flashed, boot into it and flash orangefox zip. All the rom I build are flashed with orangefox recovery, and I do not accept complains if something goes wrong using other recoveries. TWRP might work, but I haven't tested it and probably I never do it having a perfectly working and well looking recovery where orangefox is.

## How to flash `rom`?

If you are coming from another rom you **<ins>MUST</ins>** do a **clean flash**:

* Boot orangefox recovery
* Tap the trash can at the bottom of the screen, then "Format data" up right
* Type "yes" and swipe
* Go flash the rom you want
* *Optional* Flash gapps if you use them
* Reboot system  
No other steps needed, no other format, reboots and stuff is needed.

If you are coming from the same rom, you can dirty flash **<ins>WHEN NOT SPECIFIED OTHERWISE</ins>**:

* Boot orangefox recovery
* Flash rom
* *Optional* Flash gapps if you had them and if they didn't restored automatically
* Wipe dalvik/ART cache
* Reboot system.

## Which gapps should i use?

Every gapps package is fine. Choose what you like, and if someone doesn't work or simply doesn't meet your needs, flash another one. Personally, I always used NikGapps core.

## When `rom` will be updated?

Keep in mind that what I do isn't a job. Said that, you need to know that I want this device updated the same as you want. Every month, I always am informed when google releases the montly security patches, and when every roms merge the code in. When the rom has merged the code, I instantainly sync and build (if I'm at home). So please be patient and avoid to ask.

## Can you build `rom`?

As said above, this is not a job, and I do not have a nasa computer.. I always do my best to try bring the most used and worthly roms, and they already are. I'm not intrested to build other roms, they basically are all the same.

## Can you add `feature`?

My work is to pickup the rom source, mix with the device source and build. I'm not a rom developer, so ask the rom project admin or just wait to be implemented, expecially in early android versions state. For device side, as I mentioned above, I love to have always the device up-to-date. So it's useless asking the same things every day. When I'm free and have time, I "try" to do it. "Try" because not everything is possible.

I know it's the simplest way to ask even the most simple questions, but isn't better to know by yourself?

With love, your melo159😘❤️
