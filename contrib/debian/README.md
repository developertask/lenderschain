
Debian
====================
This directory contains files used to package lenderschaind/lenderschain-qt
for Debian-based Linux systems. If you compile lenderschaind/lenderschain-qt yourself, there are some useful files here.

## lenderschain: URI support ##


lenderschain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lenderschain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lenderschainqt binary to `/usr/bin`
and the `../../share/pixmaps/lenderschain128.png` to `/usr/share/pixmaps`

lenderschain-qt.protocol (KDE)

