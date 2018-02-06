#!/bin/bash
#Xee Ho Vang
#Chapter 4 script

#view partition table
parted -l

#view current mounted filesystem staues
mount 

#seeing debugg messages
sudo dmesg | less

#view Universally Unique Identify  (UUID)

#view the size and utilization fo the currently mounted filesystems
df

#check for errors without modifying anything
fsck -n /dev/sdb1

#linking two files to the same location
mkdir dir_1
mkdir dir_2
echo a > dir_1/file_1
echo b > dir_1/file_2
echo c > dir_2/file_3
ln dir_1/file_1 dir_2/file_3

#view inode status
ls -i

echo "This is my script for chapter 4. Please review and leave comments."

