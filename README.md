.img for floppy
<br/>
.iso for cd/dvd

software used:
<br/>
used [plpcfgbt 0.11](https://download.plop.at/files/bootmngr/plpcfgbt-0.11.zip) to modify plpbt.bin
<br/>
used [winimage](http://www.winimage.com/download.htm) to edit plpbt.img
<br/>
used [plpbt-createiso](https://download.plop.at/files/bootmngr/plpbt-createiso.zip) to create plpbt.iso

changes:
- disabled windows zoom animation
- changed video mode to 80x50 (text mode) [now the background looks like ["you need to insert your disc into the ps1"](https://www.avid.wiki/File:PlayStation_(Disc_read_error,_SCPH-5502).png) ahh] also must be used for systems with very low ram (ex: 8MB) or else you cant see menu if you use anything other then text mode
- disabled starfield (uses resources and is useless, "rise and shine mr. freeman" ahh)
- forces usb 1.1 (mode 1) [[booting from usb on older systems without forcing usb 1.1 freezes plop if the device doesn't support usb 2](https://forum.plop.at/index.php?topic=1104.0)]
- changed font to bios rom font (i believe there are some issues with the default font on older systems, will add another version with regular font)

download - [plop boot manager](https://www.plop.at/en/bootmanager/download.html) 
