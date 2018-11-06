
Debian
====================
This directory contains files used to package FDMd/FDM-qt
for Debian-based Linux systems. If you compile FDMd/FDM-qt yourself, there are some useful files here.

## FDM: URI support ##


FDM-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install FDM-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your FDMqt binary to `/usr/bin`
and the `../../share/pixmaps/FDM128.png` to `/usr/share/pixmaps`

FDM-qt.protocol (KDE)

