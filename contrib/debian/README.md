
Debian
====================
This directory contains files used to package cognitiod/cognitio-qt
for Debian-based Linux systems. If you compile cognitiod/cognitio-qt yourself, there are some useful files here.

## cognitio: URI support ##


cognitio-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cognitio-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cognitioqt binary to `/usr/bin`
and the `../../share/pixmaps/cognitio128.png` to `/usr/share/pixmaps`

cognitio-qt.protocol (KDE)

