# gksu

Thunar's Admin Mode

## Description

gksu is a frontend to su and gksudo is a frontend to sudo. Their primary purpose is to run graphical commands that need root without the need to run an X terminal emulator and using su directly. 

## Code

```bash
#!/usr/bin/env xdg-open
[Desktop Entry]
Version=1.0
Type=Application
Exec=gksu thunar
Terminal=false
Icon=/home/eric/Pictures/admin.png
Icon[en_US]=/home/eric/Pictures/admin.png
Name=gksu
Name[en_US]=gksu
GenericName=gksu
Comment=Thunar Admin Mode
Comment[en_US]=Thunar Admin Mode
```
