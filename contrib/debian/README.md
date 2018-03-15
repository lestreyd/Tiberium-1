
Debian
====================
This directory contains files used to package tiberiumd/Tiberium-qt
for Debian-based Linux systems. If you compile tiberiumd/Tiberium-qt yourself, there are some useful files here.

## Tiberium: URI support ##


Tiberium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Tiberium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tiberiumqt binary to `/usr/bin`
and the `../../share/pixmaps/tiberium128.png` to `/usr/share/pixmaps`

Tiberium-qt.protocol (KDE)

