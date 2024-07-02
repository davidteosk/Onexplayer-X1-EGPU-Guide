# eGPU Installation Guide (onexGPU or Nvidia) (Usb4 or Oculink)
This installation apples to egpu installs guide for either USB4 / Oculink / USB4 + Oculink connections.

## Summary of what we need to do:
1. Need to clean up all residue of existing installed Graphic Drivers. Intel and AMD.
2. We will use DDU software to clean up the drivers in Safe Mode. Need to do twice for both Intel and then AMD.
3. Then we shall install the dGPU driver first for AMD (onexgpu) or Nvidia/AMD for egpu enclosure.
4. once the dGPU driver are installed successfully, we shall install intel Arc driver last.

## What you see after a successful installation.

1. Task Manager shows two graphics driver installed and working. see screenshots.
![Pasted image 20240429062410](https://github.com/davidteosk/Onexplayer-X1-EGPU-Guide/assets/12351598/b5680b8f-94dd-4971-8bdc-ef7229bf5a6a)


3. Device Manager shows two graphic devices installed and working.
![Pasted image 20240429062648](https://github.com/davidteosk/Onexplayer-X1-EGPU-Guide/assets/12351598/6d748423-bcbd-4693-b6a3-58af0590ad0b)

Download Preparation
1. DDU  --  
2. AMD Adrenlina Driver Full Package
3. Intel Arc Driver Full Package

# HOW TO USE OCULINK WITH X1
Recently, i finally got to use oculink with X1, here is how i connect of 100% with onexgpu

### Prerequisite
- First you need to have amd driver already installed, you can do so by only connecting usb4
- After that, you do a full shutdown

### Normal Use
- Ensure xgpu power is off (no light in the xgpu power button), and X1 is powered off.
- Connect oculink to X1
- Press the power button on xgpu (so you see the light in the power button)
- Press the power button on X1, you will see the light of power button on X1, and together the LED light of xgpu
- Until you see the OneXPlayer appeared on the screen, plug in the usb4 cable from xgpu.
- It is all done, you are now using oculink and usb4 together with your xgpu.

### For shutdown
- Shutdown normally in OS
- After shutdown, you will see the xgpu LED is still on, you unplug the usb4 cable and wait for xgpu LED goes off. The power button of xgpu is still ON at this moment.
- After the xgpu LED goes off, press the power button of xgpu to turn it off.
- Ensure no LED and no power button light on xgpu, you are now safe to unplug the oculink cable from X1.

### Caution about shutdown
- If you keep the power button ON of xgpu, and do not unplug oculink cable, power will still go from xgpu to X1.
- At this situation, xgpu will become very HOT few minutes later, even if X1 is not powered on.
- So remember to make sure xgpu power button light is off and unplug the oculink cable if you are not using it.

...
[Onexplayer X1 and EGPU Guide](../main/README.md)
