---
title: Linux On External Hard Drive.
date: 2024-06-26
subtitle: plug and play linux.
---

you want to use linux but also:

- don't wanna remove windows.

- don't wanna dual boot.

- don't wanna use vms/wsl/containers etc.

- you want to use linux like plug and play.

i wanted the same things too.




so i plugged my old external wd sata 140gb drive into usb port.

>note: you should buy external ssd if you are buying.

also downloaded pop-os iso file (this should work with any distro).

then i opened virtual box (yea i know you don't want to run vm but have patience).

then created the new machine with the popos name and iso file and selected 4gb ram and 6 processors.

you should decide according to your computer specs as i have 16gb and 12 processor (just be in the green line.)

then another dialog box will appear for allocate space in virtual hard disk.

here you should select an option
`Do not add a virtual hard disk`

then just go on with click next spree and now you will have a virtual machine witout virtual hardisk.

now go to the settings of that machine and go to the storage.

in storage you will see controller ide with pop-os iso file click on the iso file and there you will see a `live cd/dvd` option check that option.

after this naviagte to the usb settings and then add usb fron the `usb with green +` icon select your hard drive.

then click ok and close settings.

now start the virtual machine.

select try popos,and check from the drive app that your hard disk is mounted if not
you should mount that disk.

after that the installation is similar in any normal linux distro just select clean install and follow instruction.

after installation is completed,you can shutdown or restart(if you have doubt abouf installation) the operating system.

after that close the virtual box and restart the system and go to boot menu to select boot order and seletct usb primary boot device first.

now if you have plugged that hard drive and you restart the computer you will get the pop-os login screen.

congrats now you are using fully functioning linux.
