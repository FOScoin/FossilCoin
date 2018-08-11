
Debian
====================
This directory contains files used to package fossilcoind/fossilcoin-qt
for Debian-based Linux systems. If you compile fossilcoind/fossilcoin-qt yourself, there are some useful files here.

## fossilcoin: URI support ##


fossilcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fossilcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fossilcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/fossilcoin128.png` to `/usr/share/pixmaps`

fossilcoin-qt.protocol (KDE)

