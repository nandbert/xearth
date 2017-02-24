to compile as nice X11 background on Linux (Debian 8 Jessie) use

(as root) $ aptitude install xorg-dev libgd2-xpm-dev
$ make -f Makefile.DIST HAVE_X11=true

for anything else see README
