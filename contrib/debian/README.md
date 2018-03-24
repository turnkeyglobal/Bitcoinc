
Debian
====================
This directory contains files used to package minmontcoind/minmontcoin-qt
for Debian-based Linux systems. If you compile minmontcoind/minmontcoin-qt yourself, there are some useful files here.

## minmontcoin: URI support ##


minmontcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install minmontcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your minmontcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/minmontcoin128.png` to `/usr/share/pixmaps`

minmontcoin-qt.protocol (KDE)

