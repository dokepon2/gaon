
Debian
====================
This directory contains files used to package gaond/gaon-qt
for Debian-based Linux systems. If you compile gaond/gaon-qt yourself, there are some useful files here.

## gaon: URI support ##


gaon-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gaon-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gaon-qt binary to `/usr/bin`
and the `../../share/pixmaps/gaon128.png` to `/usr/share/pixmaps`

gaon-qt.protocol (KDE)

