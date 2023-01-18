# PKG-BackUP

## Synopsis
Modded Version of App Dumper to Backup PKG files to External HDD Named as PKG-BackUP

## Changelogs
Version 1.0:
- Added the ability to automate and copy base, update and DLC PKG from already installed App/Games to External HDD.

Version 1.1:
- Added "config.cfg" configuration file, this will allow the user to set-up following parameters (You need to add this file on root of External HDD):
  ![image](https://user-images.githubusercontent.com/77245601/166634877-726ad8e0-a672-4808-b582-0d702ed00909.png)
- Added compatibility with extended storage drive on /mnt/ext0/..
- Added Copy Percentage Progress notification.

## Special Thanks
Massive credits to the following:
- [SiSTRo](https://github.com/SiSTR0)
- [CTN](https://github.com/ctn123)
- [Bucanero](https://github.com/bucanero)
- [Al-Azif](https://github.com/Al-Azif)
- [xvortex](https://github.com/xvortex/ps4-dumper-vtx)

;
; PS4-PKG-BACKUP configuration file. Copy it to your USB disk root.

; to define a specific cusa/app to copy:
; cusa=0 - Disabled.
; if you want to copy a specific file after payload launched use following example where 12345 it's the ID number of a CUSA. Example:
; cusa=12345 -- This will direct copy CUSA12345.
cusa=0

; to define method:
; 0 - Copy Game Base Only
; 1 - Copy Game Update Only
; 2 - Copy Game DLC Only
; 3 - Copy Game Base, Update and DLC
method=3



