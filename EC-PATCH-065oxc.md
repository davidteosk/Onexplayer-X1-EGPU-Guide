# EC PATCH 0.65oxc
Issues and bug was observed on the EC version 0.65. This patches provide a quick fix to the EC to 0.65oxc

EC (Embedded Controller Version 0.65oxc ONLY GM15_DPTE_OX04_VER41.bin last dated modified: 26/March/2024 3:35pm

_**REQUIRES TO FLASH TO THE LATEST BIOS 2.42 AND EC FIRST
**_ _**IF YOU HAVE NOT DONE SO, PLEASE DO NOT USE THIS EC PATCH**_ 
## New Improvements Observed

1. Faster Bootup Sequence ~ 15sec
2. Faster Keyboard Control ~ 5sec delay for detection
3. Improved and more accurate Thermal Control for Both manual TDP control and Intel Dynamic TDP control.
4. Improved Battery Charging - resolving old unable to charge issue with X1 due to setting TDP at 35 watt.
## Download

[newX1-ECpatch-V065oxc-26032024.zip](https://github.com/davidteosk/Onexplayer-X1-EGPU-Guide/files/15167367/newX1-ECpatch-V065oxc-26032024.zip)

## VIDEO GUIDE - from OXP
https://www.youtube.com/watch?v=XRfVzZhCcHs&t=7s

## Installation Instruction

- Required a USB flash disk >1GB such as (2G/8GB/16GB/32GB)
- Maximum FAT32 partition size is restricted to 32GB and if you have a bigger USB like 64GB, you requires to format it to 32GB size partition.
- Use Disk management to create a FAT32 Partition with 32BG partition.

1. CREATE or FORMAT FAT32 partition on the USB disk with label --> SHELL
![image](https://github.com/davidteosk/Onexplayer-X1-EGPU-Guide/assets/12351598/3bd1fce6-13d1-4979-8844-c84b0d22fb27)

3. Copy all the files into the SHELL drive. Total of 2 folders and 3 files from the root directory view.
![Pasted image 20240429045731](https://github.com/davidteosk/Onexplayer-X1-EGPU-Guide/assets/12351598/13f12bec-f64f-47ee-a218-070ca6acae32)

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

[Onexplayer X1 and EGPU Guide](../main/README.md)
