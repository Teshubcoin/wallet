
Debian
====================
This directory contains files used to package teshubd/teshub-qt
for Debian-based Linux systems. If you compile teshubd/teshub-qt yourself, there are some useful files here.

## teshub: URI support ##


teshub-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install teshub-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your teshubqt binary to `/usr/bin`
and the `../../share/pixmaps/teshub128.png` to `/usr/share/pixmaps`

teshub-qt.protocol (KDE)

