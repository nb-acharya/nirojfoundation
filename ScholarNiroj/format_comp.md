## Format the pendrive in linux:

 Identify the drive

lsblk
or 
sudo fdisk -l

 Unmount it
sudo umount /dev/sdc1

 Format it

 choose the filesystem based on your use case:
 FAT32- best compability (windows, maax, linux, )

 sudo mkfs.vfat -F 32 /dev/sbc1

 exFAT -> like fat32 but supports files > 4gb
 sudo mkfs.exfaat /dev/sdc1

 ext4 -> linux-inly, best for linux use
 sudo mkfs.ext4 /dev/sdc1

 NTFS -> windows compatible, supports large files

 sudo mkfs.ntfs /dev/sbc1


 To label it:

 sudo fatlabel /dev/sdc1 "MYUSB"
 sudo exfatlabel
 sudo e2label

 