
Debian
====================
This directory contains files used to package jasmined/jasmine-qt
for Debian-based Linux systems. If you compile jasmined/jasmine-qt yourself, there are some useful files here.

## jasmine: URI support ##


jasmine-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install jasmine-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your jasmineqt binary to `/usr/bin`
and the `../../share/pixmaps/jasmine128.png` to `/usr/share/pixmaps`

jasmine-qt.protocol (KDE)

