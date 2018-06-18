
Debian
====================
This directory contains files used to package zxflead/zxflea-qt
for Debian-based Linux systems. If you compile zxflead/zxflea-qt yourself, there are some useful files here.

## zxflea: URI support ##


zxflea-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zxflea-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zxfleaqt binary to `/usr/bin`
and the `../../share/pixmaps/zxflea128.png` to `/usr/share/pixmaps`

zxflea-qt.protocol (KDE)

