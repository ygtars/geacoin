
Debian
====================
This directory contains files used to package gead/gea-qt
for Debian-based Linux systems. If you compile gead/gea-qt yourself, there are some useful files here.

## gea: URI support ##


gea-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gea-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your geaqt binary to `/usr/bin`
and the `../../share/pixmaps/gea128.png` to `/usr/share/pixmaps`

gea-qt.protocol (KDE)

