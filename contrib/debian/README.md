
Debian
====================
This directory contains files used to package dwed/dwe-qt
for Debian-based Linux systems. If you compile dwed/dwe-qt yourself, there are some useful files here.

## dwe: URI support ##


dwe-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dwe-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dweqt binary to `/usr/bin`
and the `../../share/pixmaps/dwe128.png` to `/usr/share/pixmaps`

dwe-qt.protocol (KDE)

