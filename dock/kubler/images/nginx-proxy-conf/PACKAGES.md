### kubler/nginx-proxy-conf:20181130

Built: Fri Nov 30 21:44:27 CET 2018
Image Size: 11.2MB

#### Installed
Package | USE Flags
--------|----------
app-emulation/docker-gen-0.7.4 | ``
#### Inherited
Package | USE Flags
--------|----------
**FROM kubler/musl** |
sys-libs/musl-1.1.20-r1 | `-headers-only`
**FROM kubler/busybox** |
sys-apps/busybox-1.29.0 | `make-symlinks static -debug -ipv6 -livecd -math -mdev -pam -savedconfig (-selinux) -sep-usr -syslog -systemd`
#### Purged
- [x] Headers
- [x] Static Libs
