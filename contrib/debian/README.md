
Debian
====================
This directory contains files used to package mandiked/mandike-qt
for Debian-based Linux systems. If you compile mandiked/mandike-qt yourself, there are some useful files here.

## pivx: URI support ##


mandike-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mandike-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mandike-qt binary to `/usr/bin`
and the `../../share/pixmaps/mandike128.png` to `/usr/share/pixmaps`

mandike-qt.protocol (KDE)

