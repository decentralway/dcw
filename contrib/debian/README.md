
Debian
====================
This directory contains files used to package decentralwayd/decentralway-qt
for Debian-based Linux systems. If you compile decentralwayd/decentralway-qt yourself, there are some useful files here.

## decentralway: URI support ##


decentralway-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install decentralway-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your decentralwayqt binary to `/usr/bin`
and the `../../share/pixmaps/decentralway128.png` to `/usr/share/pixmaps`

decentralway-qt.protocol (KDE)

