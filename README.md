# Bionic-Screenset-Mach3
Screenset for Mach3 tailored to Velox VR5050

FIRST Robotics Competition (FRC) Team 4909 are heavy users of our Velox 50" x 50" CNC Router. 
This project aims to streamline our interface to help us make less mestakes by presenting 
only needed relevent information when operating the machine.

This screenset is based on the work of [Physics Anonymous](http://www.physanon.com/pa-mach-3-screen-set/) and [West Coast Products](https://wcproducts.com/products/omio-cnc-and-accessories)

## Design Goals
- Ease of use for CNC New Learners
- Concise displays for common uses


## Installation
Setup

1. Find your Mach3 install directory. The typical directory location is: `C:\Mach3\`
2. Copy the `Bionic-UI` folder to the Bitmaps folder in your directory (Ex: C:\Mach3\Bitmaps)
3. Delete `splash.bmp`, `splash1.bmp`, and `splash2.bmp` files to the **Bitmaps** folder in your directory (Ex: `C:\Mach3\Bitmaps`)
4. Copy the `splash.bmp` file to the **Bitmaps** folder in your directory (Ex: `C:\Mach3\Bitmaps`)
5. Copy the `Bionic-UI.set` file to your main directory (Ex: `C:\Mach3`)
6. Launch Mach3 Software
7. From the `View` menu choose `Load Screens` then select the `Bionic-UI.set` file that you copied to the Mach3 directory
8. For best appearence: From the `Config` menu choose `General Config...`
  - in the `Screen Control` section ensure `Hi-Res Screens` box is checked
  - in the `Screen Control` section ensure `Boxed DRO's and Graphics` box is unchecked
  - in the `Startup Modals` section ensure the `Initialization String` contains `G80 G20` (to Cancel Cycles and set Units to Inches)
9. Relaunch Mach3
