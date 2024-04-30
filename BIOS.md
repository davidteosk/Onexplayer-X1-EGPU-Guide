# BIOS (OXC OFFICIAL VERSION) 2.42 + EC 0.65
## BIOS 2.42
1. Optimize the Oculink interface to connect the graphics card dock to improve stability
2. Enable Intel Intelligent Dynamic Mode (DTT)
3. BIOS version updated to 2.42

## EC 0.65
1. Control and notify the BIOS to enable the intel Intelligent Dynamic Mode (DTT) feature
2. Embedded Controllers version updated to 0.65
## Download
https://cdn.discordapp.com/attachments/1185136883278295100/1230508162331836436/X1-intel-oxc-BIOS-EC-V42V65-.zip?ex=662e4d07&is=662cfb87&hm=72b0f129aff6f249d7f0def7ed91d7585ffb63435bee437eb50c8f6fde4142df&

## Installation Instruction

Required a USB flash disk >1GB such as (2G/8GB/16GB/32GB)
- Maximum FAT32 partition size is restricted to 32GB and if you have a bigger USB like 64GB, you requires to format it to 32GB size partition.
- Use Disk management to create a FAT32 Partition with 32BG partition.

1. CREATE or FORMAT FAT32 partition on the USB disk with label --> SHELL
2. Copy all the files into the SHELL drive. Total of 2 folders and 2 files from the root directory view
![[Pasted image 20240429045731.png]]
4. With the USB flash disk in your USB dock or usb4 interface, reboot windows to BIOS.
5. Press ESC or Delete key to enter BIOS
6. Go to the BOOT tab. Change boot sequence for #1 to Built-in EFI shell or USB DISK.
    note: the naming may varies depending on your USB flash disk.
6. Exit and Save BIOS ensuring your USB disk is plug in.
7. The Flashing software will start with 5 sec pausing showing:- press ESC to stop executing startup.nsh or press any key to proceed.
8. !!!PLEASE DO NOT PRESS ANY KEY, just wait for 5 sec to expire and it will proceed automatically.
9. The EC flashing program will starts. wait for it to completed.
10. PC will shutdown after flashing is completed.
11. Unplug and remove your USB flash DISK.
12. Press Power Button once to boot.
13. Your PC will starts in 5 sec. you should see ONEXPLAYER logo.
14. no waiting needed with EC flashing, windows will starts. If windows does not starts, go back to BIOS and change the Boot Sequence with "Windows Boot Manager" on #1
15. In windows, run System Information, you will see Embedded controller version 0.65
	- unfortunately the version is still the same as the prior.
	- but the behavior of booting is much more faster than before.

[[Onexplayer X1 and EGPU Guide]]