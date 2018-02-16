
Debian
====================
This directory contains files used to package feirmd/feirm-qt
for Debian-based Linux systems. If you compile feirmd/feirm-qt yourself, there are some useful files here.

## feirm: URI support ##


feirm-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install feirm-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your feirmqt binary to `/usr/bin`
and the `../../share/pixmaps/feirm128.png` to `/usr/share/pixmaps`

feirm-qt.protocol (KDE)

