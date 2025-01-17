## User Guide

This guide is meant as a simplified version of the firmware README, with information that is up-to-date and relevant to Rana Digital users.

The link to the Rana Digital firmware is here: https://github.com/rana-sylvatica/pico-rectangle-rana-digital

Note: currently the README in the firmware repo is unchanged from stock pico-rectangle, which is made for 20-button controllers that do not have the additional left-hand key that the Rana Digital adds.  The information on how to enter the various modes is correct, but the remapping instructions will not work because of the different number of buttons.  See the section below in this guide for how to remap the buttons on the Rana Digital.

### For Melee:

- #### PC (Slippi)

Plug the controller in using a USB-C to USB-A cable.  In Slippi Dolphin controller configuration, set port 1 to "GameCube Adapter for Wii U".  To ensure lowest possible latency, the Rana Digital emulates a GameCube Controller connected to a GCC adapter, eliminating the need for a physical adapter.

- #### Console

Plug the controller in using a USB-C to GCC cable.

### For Ultimate:

Either plug in through a GCC adapter using the USB-C to GCC cable or plug directly into the Switch with USB-C to USB-A, while holding down MX

![image](https://github.com/rana-sylvatica/rana-digital/assets/95242582/ad19f604-cd48-4781-b0d6-d9c19b1d9b23)




### For Rivals of Aether:

Plug the controller in to the PC using a USB-C to USB-A cable while holding the highlighted key.  This will cause the controller to be recognized as an XInput device with the same control scheme as in Melee modes.

![image](https://user-images.githubusercontent.com/95242582/200223718-eafcbdc4-be48-4411-9f8e-fb916dd7b6cd.png)


### Modes

This is not an exhaustive list of all the modes available in the pico-rectangle firmware but it should contain the ones that are useful to most users.


### Remapping

To enter remapping mode, hold down the highlighted key shown below when plugging in the controller.  Release the key within 3 seconds of plugging in.

![image](https://user-images.githubusercontent.com/95242582/200223796-97b3e03c-dc03-40b4-b370-f4628a88e728.png)

After 3 seconds have passed, press the keys in the following order, corresponding to your preferred layout:

 - L
 - Left
 - Down 
 - Right
 - MX
 - MY
 - Start
 - CLeft
 - CDown
 - CUp
 - A
 - CRight
 - R
 - B
 - Y
 - X
 - LS
 - Z
 - MS
 - Up
 - DpadToggle/Up2 (depending on the mode)

Once all 21 keys have been pressed, unplug the controller and plug it in again.  If done correctly, it will now have your updated key mapping saved.  The mapping will not reset to default upon updating the firmware.

### Updating firmware

To update the firmware, first download the .uf2 file from: https://github.com/rana-sylvatica/pico-rectangle-rana-digital/releases

Then, plug in the controller to the PC while holding the highlighted key.  The controller will appear as a USB storage device.  Simply drag and drop or copy and paste the .uf2 file into this USB storage device.  The controller will disconnect and then reconnect in the default mode (emulated GCC adapter).

![image](https://user-images.githubusercontent.com/95242582/200201359-dd910422-d2cd-4318-995a-8f888dfb1723.png)

