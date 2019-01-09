
Debian
====================
This directory contains files used to package eonagend/eonagen-qt
for Debian-based Linux systems. If you compile eonagend/eonagen-qt yourself, there are some useful files here.

## eonagen: URI support ##


eonagen-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install eonagen-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your eonagenqt binary to `/usr/bin`
and the `../../share/pixmaps/eonagen128.png` to `/usr/share/pixmaps`

eonagen-qt.protocol (KDE)

