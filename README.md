# rpi-transfer
A python script to transfer files to the ext partition via the FAT partition visible to Windows and Mac.
This script gets around the limitation of Windows and Mac not seeing the ext4 partition to edit files, by making a daemon that adds or modifies files, based on what is specified in the boot partition, the only part of the SD card visible to Windows and Mac.

## Files

The main script is called rpi-transfer, and everything in there is what runs. Nothing else. Not many comments are included, which is one thing to add, but most of it should be self explanatory. Under rpi_transfer are the EDIT-AND-DELETE.txt and INSTRUCTION.txt base files, and under debian are the settings for building the final .deb file.

## Todo:
- Clean up NOOBS redundancy in code
- Add settings file
- Add comments in code
- Add more logging

## Quickstart:
A quickstart is availible on the forum announcement: https://www.raspberrypi.org/forums/viewtopic.php?f=63&t=117616&p=799637

## License
This is distrubuted under the GNU General Public License v2.0. A copy of this license is included.
