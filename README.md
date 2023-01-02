**1- Bluetooth vanished or been disabled**
- On my laptop, a common solution for this problem is to reset Bluetooth with a fresh copy of frameware and overwrite it. 

1. Download FW from http://archive.ubuntu.com/ubuntu/pool/main/l/linux-firmware/linux-firmware_1.201.tar.xz   <br />
2. copy it ``` sudo cp -R ar3k /lib/firmware ```
3. restart

**Source Link:**  https://askubuntu.com/questions/1403817/i-cant-turn-on-bluetooth-in-ubuntu-22-04-lts

**2- How to extract two-part archive files on linux**
- Two-part archive files, or "split files", are archive files that have been split into multiple parts in order to make it easier to transfer them or to fit them onto removable media.


1. Use the cat command to concatenate the two parts of the archive file into a single file:
``` cat file.tar.part1 file.tar.part2 > file.tar ```

2. Extract the contents of the combined archive file using the appropriate tool:
``` unzip file.zip ```
