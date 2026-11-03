⚠️ Warning
I am not responsible for bricked devices, missing recovery partitions, dead xiaomi factoryline workers cowboys, dead pmics, dead sd cards, dead ram, dead cpus, any xiaomi shenanigans, dead cats or dogs, nuclear wars or you getting fired.

This is a delicate process, do it under your own risk and follow all the steps carefully.

IF YOU AREN'T COMFORTABLE MODDING YOUR DEVICE OR ITS PARTITION TABLE OR YOU ARE PARANOID OF BRICKING YOUR DEVICE CLICK AWAY NOW!!! (it can be fixed in a brick) YOU HAVE BEEN WARNED,YOU HAVE BEEN WARNED!!!


so this is a guide to unlock the bootloader at a mi box 4 as you may know the bootloader comes locked with no way to unlock it.
SO LAST WARNING READ THIS GUIDE AND DONT SKIP ANY STEPS IF YOU DO IT CAN BIRCK YOUR DEVICE AND DELETE NETFLIX ESN WHICH WILL BRICK NETFLIX

step 1:
prep work
first download every in [here](https://github.com/talveller/mibox4unlockbootloader/releases/tag/files)
and have a usb-a to a powered hub or usb-a to usb-c powered hub

step 2:
flash the file given the name is usb.img to a 8gb or more usb stick use rufus or something else then update your device to android 12 if you are on android 8.1 update to android 9 then android 12.
then connect the usb stick to the powered hub and a keyboard and via adb wifi and then type in adb reboot update it should boot to armbian if it doesn't you did something wrong.
if it booted to armbian follow the on screen text if there is any then run armbian-ddbr then r it will backup the os then press b and select the one thats called backup.img.gz.
it will restore the backup that has a unlocked bootloader IT WILL DELETE NETFLIX ESN OR WILL FLASH A BAD ONE SO IT WILL NOT WORK.
when it finishes reboot and it will boot to android 12 reenable adb wifi or adb and connect with a pc and type adb reboot bootloader if it doesnt work do adb reboot recovery or the button combo then reboot bootloader.
after that it will reboot to the bootloader then run fastboot getvar unlocked.
if will display unlocked: yes.
then the bootloader is unlocked and you just unlocked a mi box 4 bootloader
