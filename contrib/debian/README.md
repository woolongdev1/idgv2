
Debian
====================
This directory contains files used to package idealgoldv2d/idealgoldv2-qt
for Debian-based Linux systems. If you compile idealgoldv2d/idealgoldv2-qt yourself, there are some useful files here.

## idealgoldv2: URI support ##


idealgoldv2-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install idealgoldv2-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your idealgoldv2qt binary to `/usr/bin`
and the `../../share/pixmaps/idealgoldv2128.png` to `/usr/share/pixmaps`

idealgoldv2-qt.protocol (KDE)

