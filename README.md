# PalmerOS
My custom Debian-based operating system

rsync -av /media/cdrom/ PalmerOS

genisoimage -r -V "PalmerOS 1.0" -J -l -b isolinux/isolinux.bin -c isolinux/boot.cat -no-emul-boot -boot-load-size 4 -boot-info-table -o ../PalmerOS.iso /root/PalmerOS/