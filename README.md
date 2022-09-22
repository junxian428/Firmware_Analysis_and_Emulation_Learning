# Firmware_Analysis_and_Emulation_Learning

Download Firmware 

binwalk XXX.bin 

dd if=XXX skip=XXX bs=1 of=dlink.sqsh

______________________________________________________________________________________________

# Download Emulator

sudo apt -y install qemu-user-static

_________________________________________________________________________________________________

sudo unsquashfs dlink.sqsh

_________________________________________________________________________________________________________

cd squash-root

ls


file bin/busybox

—————————————————————————————————————————————————————————————————————————————————————————————————————————

qemu-mips-static bin/busybox


____________________________________________________________________________________________________________

sudo mount --bind /sys /home/kali/Downloads/squashfs-root/sys

sudo mount --bind /dev /home/kali/Downloads/squashfs-root/dev

sudo mount --bind /proc /home/kali/Downloads/squashfs-root/proc

sudo chroot . /bin/sh

_______________________________________________________________________________________________________________

netstat -tln


Now go to port:XX should can see the IPCamera for our case.
