# rpi-transfer
A python script to transfer files to the ext partition via the FAT partition visible to Windows and Mac.
This script gets around the limitation of Windows and Mac not seeing the ext4 partition to edit files, by making a daemon that adds or modifies files, based on what is specified in the boot partition, the only part of the SD card visible to Windows and Mac.

## Files

The main script is called rpi-transfer, and everything in there is what runs. Nothing else. Not many comments are included, which is one thing to add, but most of it should be self explanatory.

## License
This is distrubuted under the GNU General Public License v2.0. A copy of this license is included.