
Debian
====================
This directory contains files used to package astercoind/astercoin-qt
for Debian-based Linux systems. If you compile astercoind/astercoin-qt yourself, there are some useful files here.

## astercoin: URI support ##


astercoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install astercoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your astercoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/astercoin128.png` to `/usr/share/pixmaps`

astercoin-qt.protocol (KDE)

