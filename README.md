# gOS
A operating system made with the GRUB shell.
This project uses the GRUB bootloader which can be found and downloaded from https://www.gnu.org/software/grub/grub-download.html.
# Installation
Assuming you are using Ubuntu:
```bash
sudo apt-get install grub2-common grub-pc-bin xorriso
git clone https://github.com/programmeruser2/gOS.git
cd gOS
grub-mkrescue -o gOS.iso iso
```
To run this in QEMU:
```bash
qemu-system-i386 -cdrom gOS.iso
```
