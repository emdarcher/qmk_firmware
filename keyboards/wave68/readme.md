# The WAVE68 keyboard 

![wave68](imgur.com image replace me!)

A short description of the keyboard/project

Keyboard Maintainer: [emdarcher](https://github.com/emdarcher)  
Hardware Supported: WAVE68   
Hardware Availability: links to where you can find this hardware

Make example for this keyboard (after setting up your build environment):

    make wave68:default

To compile for a specific revision (ex. rev0):

    make wave68/rev0:default

To activate the USBasploader bootloader hold down the BOOT button during power on or reset and the on-board LED should light up.

After activating the bootloader, you can program the WAVE68 by running the `make` command with the `program` parameter as shown in the example below:

    make wave68:default:program

After flashing the board, reset it, and it should be running your new firmware.


See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
