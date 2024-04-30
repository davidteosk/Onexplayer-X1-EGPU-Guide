# eGPU Installation Guide (onexGPU or Nvidia) (Usb4 or Oculink)
This installation apples to egpu installs guide for either USB4 / Oculink / USB4 + Oculink connections.

## Summary of what we need to do:
1. Need to clean up all residue of existing installed Graphic Drivers. Intel and AMD.
2. We will use DDU software to clean up the drivers in Safe Mode. Need to do twice if necessary for Intel and then AMD.
3. Then we shall install the dGPU driver first for AMD (onexgpu) or Nvidia/AMD for egpu enclosure.
4. once the dGPU driver are installed successfully, we shall install intel Arc driver last.

## What you see after a successful installation.

1. Task Manager shows two graphics driver installed and working. see screenshots.
![[Pasted image 20240429062410.png]]

2. Device Manager shows two graphic devices installed and working.
![[Pasted image 20240429062648.png]]

Download Preparation
1. DDU  --  
2. AMD Adrenlina Driver Full Package
3. Intel Arc Driver Full Package
