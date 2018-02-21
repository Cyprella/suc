
Debian
====================
This directory contains files used to package sucd/suc-qt
for Debian-based Linux systems. If you compile sucd/suc-qt yourself, there are some useful files here.

## suc: URI support ##


suc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install suc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your suc-qt binary to `/usr/bin`
and the `../../share/pixmaps/suc128.png` to `/usr/share/pixmaps`

suc-qt.protocol (KDE)

