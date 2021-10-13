
Debian
====================
This directory contains files used to package skoncoind/skoncoin-qt
for Debian-based Linux systems. If you compile skoncoind/skoncoin-qt yourself, there are some useful files here.

## skoncoin: URI support ##


skoncoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install skoncoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your skoncoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/skoncoin128.png` to `/usr/share/pixmaps`

skoncoin-qt.protocol (KDE)

