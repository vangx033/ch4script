#!/bin/bash
#Xee Ho Vang
#Chapter 4 script

#view current mounted filesystem staues
mount | less | pr 

#seeing debugg messages
sudo dmesg | less |pr

#view Universally Unique Identify  (UUID)
sudo blkid

#view the size and utilization fo the currently mounted filesystems
df

#check for errors without modifying anything
sudo fsck -n /dev/sda

#create a symbolic link and point file1 to link1 and verify it
ln -s file_1 link1
ls -l file1 link1

#view inode status
ls -i

echo "This is my script for chapter 4. Please review and leave comments."

