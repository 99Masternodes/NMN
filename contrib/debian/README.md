
Debian
====================
This directory contains files used to package nmnd/nmn-qt
for Debian-based Linux systems. If you compile nmnd/nmn-qt yourself, there are some useful files here.

## nmn: URI support ##


nmn-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nmn-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nmnqt binary to `/usr/bin`
and the `../../share/pixmaps/nmn128.png` to `/usr/share/pixmaps`

nmn-qt.protocol (KDE)

