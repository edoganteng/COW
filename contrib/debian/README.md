
Debian
====================
This directory contains files used to package cowryd/cowry-qt
for Debian-based Linux systems. If you compile cowryd/cowry-qt yourself, there are some useful files here.

## cowry: URI support ##


cowry-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cowry-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cowryqt binary to `/usr/bin`
and the `../../share/pixmaps/cowry128.png` to `/usr/share/pixmaps`

cowry-qt.protocol (KDE)

