
Debian
====================
This directory contains files used to package ampd/amp-qt
for Debian-based Linux systems. If you compile ampd/amp-qt yourself, there are some useful files here.

## amp: URI support ##


amp-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install amp-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ampqt binary to `/usr/bin`
and the `../../share/pixmaps/amp128.png` to `/usr/share/pixmaps`

amp-qt.protocol (KDE)

