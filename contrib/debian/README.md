
Debian
====================
This directory contains files used to package travelpayd/travelpay-qt
for Debian-based Linux systems. If you compile travelpayd/travelpay-qt yourself, there are some useful files here.

## travelpay: URI support ##


travelpay-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install travelpay-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your travelpayqt binary to `/usr/bin`
and the `../../share/pixmaps/travelpay128.png` to `/usr/share/pixmaps`

travelpay-qt.protocol (KDE)

