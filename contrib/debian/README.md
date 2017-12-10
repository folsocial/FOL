
Debian
====================
This directory contains files used to package fold/fol-qt
for Debian-based Linux systems. If you compile fold/fol-qt yourself, there are some useful files here.

## fol: URI support ##


fol-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fol-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fol-qt binary to `/usr/bin`
and the `../../share/pixmaps/fol128.png` to `/usr/share/pixmaps`

fol-qt.protocol (KDE)

