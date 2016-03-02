# vnc-helper

![screenshot](/screenshot.png?raw=true "window")

Little script, which launches x11vnc server with random password

## Build deb

apt-get install fakeroot dpkg debconf debhelper

fakeroot dpkg-deb --build vnc-helper
