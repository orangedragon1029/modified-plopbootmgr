.img for floppy
<br/>
.iso for cd/dvd

software used:
<br/>
used plpcfgbt 0.11 (https://download.plop.at/files/bootmngr/plpcfgbt-0.11.zip) to modify plpbt.bin
<br/>
used winimage to edit plpbt.img
<br/>
used plpbt-createiso (https://download.plop.at/files/bootmngr/plpbt-createiso.zip) to create plpbt.iso

changes:
- disabled windows zoom animation
- changed video mode to 80x50 (text mode)
- disabled starfield (uses resources and is useless, "rise and shine mr. freeman" ahh)
- forces usb 1.1 (mode 1) [booting from usb on older systems without forcing usb 1.1 freezes plop if the device doesn't support usb 2]
- changed font to bios rom font (i believe there are some issues with the default font on older systems, will add another version with regular font)
<br/>
plop boot manager - https://www.plop.at/en/bootmanager/download.html</p>
