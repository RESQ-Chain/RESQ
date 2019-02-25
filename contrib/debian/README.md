
Debian
====================
This directory contains files used to package resqd/resq-qt
for Debian-based Linux systems. If you compile resqd/resq-qt yourself, there are some useful files here.

## resq: URI support ##


resq-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install resq-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your resqqt binary to `/usr/bin`
and the `../../share/pixmaps/resq128.png` to `/usr/share/pixmaps`

resq-qt.protocol (KDE)

