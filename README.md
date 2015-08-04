# rpi-transfer
A python script to transfer files to the ext partition via the FAT partition visible to Windows and Mac.
This script gets around the limitation of Windows and Mac not seeing the ext4 partition to edit files, by making a daemon that adds or modifies files, based on what is specified in the boot partition, the only part of the SD card visible to Windows and Mac.
