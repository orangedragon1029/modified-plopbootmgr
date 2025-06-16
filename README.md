.img for floppy
.iso for cd/dvd

used plpcfgbt 0.11 to modify plpbt.bin
changes:
- disabled windows zoom animation
- changed video mode to 80x50 (text mode)
- disabled starfield (uses resources and is useless)
- forces usb 1.1 (mode 1) [booting from usb on older systems without forcing usb 1.1 freezes plop if the device doesn't support usb 2]
- changed font to bios rom font (i believe there are some issues with the default font on older systems, will add another version with regular font)
