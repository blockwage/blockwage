
Debian
====================
This directory contains files used to package blockwaged/blockwage-qt
for Debian-based Linux systems. If you compile blockwaged/blockwage-qt yourself, there are some useful files here.

## blockwage: URI support ##


blockwage-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install blockwage-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your blockwageqt binary to `/usr/bin`
and the `../../share/pixmaps/blockwage128.png` to `/usr/share/pixmaps`

blockwage-qt.protocol (KDE)

