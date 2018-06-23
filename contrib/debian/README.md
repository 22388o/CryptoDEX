
Debian
====================
This directory contains files used to package cryptodexd/cryptodex-qt
for Debian-based Linux systems. If you compile cryptodexd/cryptodex-qt yourself, there are some useful files here.

## cryptodex: URI support ##


cryptodex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cryptodex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cryptodex-qt binary to `/usr/bin`
and the `../../share/pixmaps/cryptodex128.png` to `/usr/share/pixmaps`

cryptodex-qt.protocol (KDE)

