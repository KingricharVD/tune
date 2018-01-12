
Debian
====================
This directory contains files used to package tuned/tune-qt
for Debian-based Linux systems. If you compile tuned/tune-qt yourself, there are some useful files here.

## tune: URI support ##


tune-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tune-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tune-qt binary to `/usr/bin`
and the `../../share/pixmaps/tune128.png` to `/usr/share/pixmaps`

tune-qt.protocol (KDE)

