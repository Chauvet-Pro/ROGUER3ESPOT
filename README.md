# ROGUER3ESPOT

## Software Versions

[V1.241113 - Rogue R3E Spot](https://github.com/Chauvet-Pro/ROGUER3ESPOT/blob/3724ce3084ffd9850159f67d279b8a542483ae01/firmware/V1.241113.zip)
- No new features or performance enhancements were added. This update is for internal use only

[V1.240123 - Rogue R3E Spot](https://github.com/Chauvet-Pro/ROGUER3ESPOT/blob/eca09a339563690fe8703ea42da2dac26a17d4ab/firmware/V1.240123.zip)
- Added stop point to gobo rotating channel

[V1.240428 - Rogue R3E Spot](https://github.com/Chauvet-Pro/ROGUER3ESPOT/blob/eca09a339563690fe8703ea42da2dac26a17d4ab/firmware/V1.240428.zip)
- Improved temperature control during gobo rotation

  &nbsp;

## USB Software Update Instructions
1.  Power on the product and plug the flash drive into the USB port.
2.	Once the flash drive has been detected, the message “***USB Update***” will be displayed. Press **< YES >**.
3.	The next screen will show the software versions available for this fixture on the USB drive. For multiple versions of the software for the same fixture, use **< UP >** or **< DOWN >** to select the desired version. Press **< ENTER >**.
4.	The ***"USB Update*** screen will re-appear. Press **< YES >**.
5.	The upgrade will start. DO NOT turn off the power or disconnect the USB while the USB LED is still blinking during the process. The screen display will read: ***"USB Update Wait"***. USB update can take several minutes to complete.
    > When the USB stops blinking, all the motors will power down, and the display will go blank. DO NOT turn off the power. The fixture will automatically reboot when the update is done.
6.  Go to **Sys Info** on the fixture's menu map and confirm the firmware revision.
7.	When the boot-up process is finished, restart the fixture.


### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with FAT32 file format.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need the **UPLOAD 08** device to fix this. 
