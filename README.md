# Author:JavaBabyX adaptation of Lâm Minh Thiện's https://github.com/lamminhthien-ntu/OneUI-3.1-Debloat-for-Battery-Optimize
# Country: ZA ,Vietnam
# Tested Device: Galaxy A31 & A10f XFA (SM-A315G XXV)
# One UI 3.1 (  May be One UI 3.1 Core Version Can use this code)
# Email Original dev Contact://, minhthienmap@gmail.com 
# How to use Code:
 * https://www.youtube.com/watch?v=MIUB2myx7Tw&t=362s Thanks to channel: Viettablet 
 * Open File V1.5.5 with Raw
# Find and add more packages
 * Use Find (CTRL+F) with keyword 'hearingadjust' and using command: pm install-existing <package name> to re install it again.
 ** f you'd like to see and find packages to add features... just open another cmd with adb copy and paste and look for apss or packages folder:
            adb shell; cd /system/;
*to search auto you could possibly use: ls /*/*.apk
       **if it finds nothing add /* to the start of /*/*.apk
# OneUI 3.1 Debloat Packages List
# Research by me and from XDA Forum
# faster boot-time and more overall system respnsiveness
# Retains common function, feautures, and all Google Services for convinience.
# as long as you do not touch ui,system and most .sec apps there should be no issues
# All Call Function Test ok. (include call recorder)
* Google Test ok.
* Chrome Test ok.
* Gmail Test ok.
* Google Map ok.
* Phone ok.
* CH Play ok.
* Facebook, Messenger ok.
* Camera ok.
* Gallarey ok.
* Clock ok.
* Contact ok.
* Settings :
  * Accessbility ok.
  * Advanced Feautures ok
  * Wallaper ok
  * Screen setting ok.
  * Application manager ok.
  * Permission Controller ok.
  * Fingerprint ok
  * Lockscreen option ok.
  * Notification setting ok.
  * Wifi List, Wifi Scan, Wifi connect, Wifi QR Code: ok.
  * Wifi Direct ok.
  * Bluetooth find ok., Bluetooth Connect ok.
  * NFC: Not / for A10f,the a5f has support but adnroid 7
    * Scan: ok
    * Payment: Yes.
    * LTE,4g,3g: ok
    * Data Usage: ok
    * Sim manager: ok
    * Airplane mode: ok
    * Internet Tethering: ok
    * Wifi sharing: ok
    * VPN (1.1.1.1 WARP): ok.
    * Print service: Unninstall Default Print Service, but You can install another Print Service to use.
    * DNS Custom: Yes
    * Sound settings: Yes
    * Picker Alarm: No (But you can reinstall via "soundpicker")
    * Dobly Atmos: Yes
    * All other function good.
* Calendar ok.
* Battery Saver ok
* Night mode ok.
* Restriction ok.
* QR Camera Scan ok.
* GPS function ok.
* Alway On Display ok.
* Torch ok.
* Screen orientation ok.
* Adaptive brightness ok.
* SIM Selection for Call and Mobile Network ok.
* Voice Record ok


# Performance Review (Comparision after and before debloat):
* Reduce boot times. yes (fast than 10 second)
* Fast Open System App:
 * Phone: Open Time reduce 1 second, Setting open less than 0.3 second
 * Message: Open time reduce 2 second, Open and message fast, 
 * Galarey open very fast
 * Google open very fast, swich between many layout quickly.
 * Google Speak microphone icon appear very quickly
 * CH Play very very fast, choose app to download very fast, change category very fast, search app very fast, App manager very fast
 * Chrome improve startup time, Loading news fast, load amazon web fast, load espn.com improved time, play video on espn.com still slow, but fast and acceptable
 * Gmail reduce time a bit.
 * Goolge Map loading very fast, all other function fast and big improved
 * FAcebook loading very quickly, a big improved, all funciton fast and big improve
 * Messenger, big improved.
 * Callendar, big improved.
 * Zing mp3: big improved
 * Calculator: big improved
 * Youtube: big improved.
 * Soundcloud: big improved
 * Zalo: big improved.
 * Office: a bit improved.
 * Device care: big improved time loading.
 * Bilibili: Improved loading time, video thumbnail load faster
 * Pixiv: Improved loading time, picture load very fast than before
# Final Conclusion: Using phone make me feeling very happy, touch and application respone, render smooth and ligntning fast. Alwesome more than The first time I'm using this phone. And advance review I'll write, when i have time
# Advanced Performance Review (Comming Soon).
# Moba Game Arena Of Valor Test:
 * Setting High Except HD mode unable to set
 * High Frame Rate Enable via * Unlock File*
    --> Result: Doesn't meet fps drop annymore especially when combat  (Test with 22.75 minutes Ranking Diamond IV battle)
