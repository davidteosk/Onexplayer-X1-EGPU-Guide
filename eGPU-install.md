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



...
[Onexplayer X1 and EGPU Guide](../main/README.md)
