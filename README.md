First off doing this will void your warranty and can brick your device. Following these simple steps should work for you. 
I will state here and further down, make sure you download all programs needed and both recovery.img and recovery_orig.img. 
I am in no way resposible for your device being bricked. 

**Only thing I have not tested is the external sd card, I make no promises that it works. I only have 1 sd micro card its 
installed in my main device. So install the recoveries and supersu to your internal sdcard.

This is for assurance wireless, I have seen one or two other n817 devices if the specs are the same, they "should" work 
with this twrp, but use partition backup and restore by wanam on Play store to get a recovery.img for your device. I do 
not use this program for system back up, for some reason it does not work properly but its fine for boot,aboot, recovery 
and other smaller partitions. 

This is a ported twrp from kis3 twrp version 3.0.2-0 by KonstaT from here http://konstakang.com/devices/kis3/TWRP/. 
Also this version of chainfire su SR3-SuperSU-v2.79-SR3-20170114223742 download from here https://download.chainfire.eu/1021/.

Other programs needed [ROOT]Rashr flash tool, online nandroid backup *root*, SD maid from Play Store. The Rashr flash tool is
required, you can use any back up you wish, I prefer SD maid for cleaning up system and removing/freezing programs you can use 
any you use, this is to remove your temp root after recovery and supersu is installed.

**Again I am stating here the Rashr flash tool is required this will allow you to install the recovery.img with a locked 
bootloader. This is a must to install this twrp recovery. The twrp app will not work until you have supersu installed. 
There are other flash tools, but this worked flawless with kingo so its the only one I will support for this guide. If you use 
another flash tool its on you. 

The twrp for the twrp n817 recovery.img along with recovery_orig.img go here 
 
First make a back up prior to installing the twrp recovery. Use the online nandoird back up of all partitions I save them as 
twrp. If you have external SD card you can do all at once if not do all but data and system then copy to your computer 
and then back up system folder. Your choice on data, I back up my apk so never data. 

Next run Rashr flash tool from Play store the first option is recovery from storage, choose this option then go to your 
location on sdcard and select recovery.img hit ok it will take about 10 to 15 seconds and ask if you want to reboot into recovery,
hit yes and then your device will reboot into recovery. Once loaded swipe and go to install, top left find your 
SR3-SuperSU-v2.79-SR3-20170114223742.zip file and select that, then swipe to install. 
Once finished hit reboot and system. 

You now have a twrp recovery, and chainfire's supersu installed on your n817 device.
