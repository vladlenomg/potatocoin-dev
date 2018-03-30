
Debian
====================
This directory contains files used to package potatod/potato-qt
for Debian-based Linux systems. If you compile potatod/potato-qt yourself, there are some useful files here.

## potato: URI support ##


potato-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install potato-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your potato-qt binary to `/usr/bin`
and the `../../share/pixmaps/potato128.png` to `/usr/share/pixmaps`

potato-qt.protocol (KDE)

