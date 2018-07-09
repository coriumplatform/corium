
Debian
====================
This directory contains files used to package coriumd/corium-qt
for Debian-based Linux systems. If you compile coriumd/corium-qt yourself, there are some useful files here.

## corium: URI support ##


corium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install corium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your coriumqt binary to `/usr/bin`
and the `../../share/pixmaps/corium128.png` to `/usr/share/pixmaps`

corium-qt.protocol (KDE)

