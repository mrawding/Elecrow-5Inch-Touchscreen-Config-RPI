# Elecrow-5Inch-Touchscreen-Config-RPI
A repository for setting up and configuring Elecrow Touchscreens on Raspberry PIs


## Information and Expected Results By The End

This repository supports the  5 inch touchscreen(s) from Elecrow. Depending on the type of screen you have, you'll need to figure out if this is the capactive touch screen [QDtech MPI5001](https://www.elecrow.com/5-inch-hdmi-800-x-480-capacitive-touch-lcd-display-for-raspberry-pi-pc-sony-ps4.html) that supports multi-touch OR the resitive single touch screen TFT [ADS7846 Touchscreen](https://www.elecrow.com/hdmi-5-inch-800x480-tft-display-for-raspberry-pi-b-p-1384.html) display.

This project assumes the device is an 800x480 display.

By the end you'll have the following setup.

**DUAL Mixed Virtual/Physical Display**
- 800x480 Physical Display on the touch screen
- 1920x1080 Virtual Display to connect via VNC server
- Calibrated X11 touchscreen mappings to the touchscreen devices. If multi-touch is supported it will be multi-touch inputs to X11.
- Primary display on VNC server, Secondary display on Physical device.


## Getting Started with Capactive Touch Display

#### Install the boot configuration.

The script will automatically back up your /boot/config.txt and enumerate any existing backups, but to be safe overlook your current config to make sure any differences between the one you are about to install and your current one will be kept. Also maintain your own backup copy.

Reboot


#### Install X11 mappings and calibrations. 

You can run the calibrator for yourself if you want, but if you only have the display connected and no other displays- then the pre-existing cal in this repository should work perfectly fine.


#### Reboot or restart the mappping service





## Getting Started with Resistive Touch Display



