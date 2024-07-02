# BIOS 2.45 (1/7/2024)

# Download X1-BIOS-MEMORY-V45.ZIP
MEGA: 

VT-d Menu (green): if you dont need to run virtualisation eg VM's
Disabled everything here

Memory Configuration(red):
DO NOT TOUCH everything is set to best performance by default 

![bios245-VT-d](https://github.com/davidteosk/Onexplayer-X1-EGPU-Guide/assets/12351598/a7f59273-cbda-4adc-a1cc-f4dc1abedd73)

## Change log:
So should boost performance in memory bandwidth bottlenecked games and slightly improve ipc with vt-d disabled
Flashable in windows, make sure to disable defender before flashing, make sure to disable bitlocker on drives as well if using.
You may need to add the folder you download the bios file to a whitelist if you have issues downloading 
Pin will be reset so make sure you have a normal windows password set before flashing
After reboot just be patient and let windows boot might take awhile but don't force a shut down.
Also no need to change anything memory config, but you can disabled everything in the vt-d menu if you arent using virtualisation 
1. Optimize the Oculink interface to connect the graphics card dock to improve stability
2. Enable Intel Intelligent Dynamic Mode (DTT)
3. BIOS version updated to 2.42



# The key is understanding whether your game is CPU bottlenecked, GPU bottlenecked, or both and setting the OXC settings appropriately.

If it's a game that's heavily CPU bottlenecked on single threads with lower GPU requirements (i.e. Destiny 2), use:
OXC settings -> Intel Turbo Boost: off
OXC settings -> Intel dynamic performance mode: on
OXC main page -> Turbo On
OXC main page: Intel dynamic performance mode: high perform
Windows "Power sleep and battery settings": do NOT change this from "best power efficiency" which OXC should automatically set when you turn on high performance DTT mode
Windows refresh rate in Windows Display Settings: 60

If it's a game that's heavily GPU bottlenecked, with lower CPU requirements, use:
OXC settings -> Intel Turbo Boost: off
OXC settings -> Intel dynamic performance mode: on
OXC main page -> Turbo Off
OXC main page: Intel dynamic performance mode: high perform
Windows "Power sleep and battery settings": do NOT change this from "best power efficiency" which OXC should automatically set when you turn on high performance DTT mode
Windows refresh rate in Windows Display Settings: 60

If it's a game with balanced CPU and GPU requirements, use the setting for GPU bottlenecked games above, with the note that you might have to set vsync in-game to 1/2 framerate (i.e. 30 FPS).
In addition, as Jaige said, it's a matter of setting graphical settings to low (including the advanced settings), using XESS where available in ulta performance mode / FSR2 in ultra performance mode if XESS is not available / setting res to 1280x800 if neither are available, and then work up from there if performance is acceptable, increasing textures to medium first, testing again, then bumping up other settings until you notice framerate issues. 

# All oxp devices support bypass charging once at 100% it does not use the battery at all and just powers the device directly

....
[Onexplayer X1 and EGPU Guide](../main/README.md)
