
Debian
====================
This directory contains files used to package brigd/brig-qt
for Debian-based Linux systems. If you compile brigd/brig-qt yourself, there are some useful files here.

## brig: URI support ##


brig-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install brig-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your brigqt binary to `/usr/bin`
and the `../../share/pixmaps/brig128.png` to `/usr/share/pixmaps`

brig-qt.protocol (KDE)

