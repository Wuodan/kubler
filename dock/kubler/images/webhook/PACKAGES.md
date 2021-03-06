### kubler/webhook:20181130

Built: Mon Dec  3 13:41:07 CET 2018
Image Size: 79.1MB

#### Installed
Package | USE Flags
--------|----------
app-admin/metalog-3-r2 | `unicode`
app-arch/bzip2-1.0.6-r10 | `-static -static-libs`
app-crypt/gnupg-2.2.10 | `bzip2 nls readline ssl -doc -ldap (-selinux) -smartcard -tofu -tools -usb -wks-server`
app-crypt/pinentry-1.1.0-r2 | `ncurses -caps -emacs -fltk -gnome-keyring -gtk -qt5 -static`
app-eselect/eselect-lib-bin-symlink-0.1.1 | ``
app-eselect/eselect-pinentry-0.7 | ``
dev-libs/gmp-6.1.2 | `asm cxx -doc -pgo -static-libs`
dev-libs/libassuan-2.5.1 | `-static-libs`
dev-libs/libgcrypt-1.8.3 | `-doc -o-flag-munging -static-libs`
dev-libs/libgpg-error-1.29 | `nls -common-lisp -static-libs`
dev-libs/libksba-1.3.5-r1 | `-static-libs`
dev-libs/libpcre-8.41-r1 | `bzip2 cxx readline recursion-limit (unicode) zlib -jit -libedit -pcre16 -pcre32 -static-libs`
dev-libs/libtasn1-4.13 | `-doc -static-libs -test -valgrind`
dev-libs/libunistring-0.9.7 | `-doc -static-libs`
dev-libs/nettle-3.4 | `gmp -doc (-neon) -static-libs -test`
dev-libs/npth-1.3 | `-static-libs`
dev-vcs/git-2.19.2 | `blksha1 curl gpg iconv nls pcre threads -cgi -cvs -doc -emacs -gnome-keyring -highlight -libressl -mediawiki -mediawiki-experimental (-pcre-jit) -perl (-ppcsha1) -python -subversion -test -tk -webdav -xinetd`
dev-vcs/webhook-2.6.9 | `minimal`
mail-mta/nullmailer-2.0-r1 | `ssl`
net-dns/libidn2-2.0.4 | `-static-libs`
net-libs/gnutls-3.5.19 | `cxx idn nls openssl seccomp tls-heartbeat zlib -dane -doc -examples -guile -openpgp -pkcs11 -sslv2 -sslv3 -static-libs -test (-test-full) -tools -valgrind`
sys-apps/shadow-4.6 | `acl cracklib nls xattr -audit -pam (-selinux) -skey`
sys-libs/cracklib-2.9.6-r1 | `nls zlib -python -static-libs`
#### Inherited
Package | USE Flags
--------|----------
**FROM kubler/bash** |
app-admin/eselect-1.4.13 | `-doc -emacs -vim-syntax`
app-portage/portage-utils-0.64 | `nls -static`
app-shells/bash-4.4_p12 | `net nls (readline) -afs -bashlogger -examples -mem-scramble -plugins`
dev-libs/iniparser-3.1-r1 | `-doc -examples -static-libs`
net-misc/curl-7.61.1 | `ssl threads -adns -brotli -http2 -idn -ipv6 -kerberos -ldap -metalink -rtmp -samba -ssh -static-libs -test`
sys-apps/acl-2.2.52-r1 | `nls -static-libs`
sys-apps/attr-2.4.47-r2 | `nls -static-libs`
sys-apps/coreutils-8.29-r1 | `acl nls split-usr (xattr) -caps -gmp -hostname -kill -multicall (-selinux) -static -test -vanilla`
sys-apps/file-5.34 | `zlib -python -static-libs`
sys-apps/sed-4.5 | `acl nls -forced-sandbox (-selinux) -static`
sys-libs/ncurses-6.1-r2 | `cxx minimal threads unicode -ada -debug -doc -gpm (-profile) -static-libs -test -tinfo -trace`
sys-libs/readline-7.0_p3 | `-static-libs -utils`
**FROM kubler/openssl** |
app-misc/ca-certificates-20170717.3.36.1 | `-cacert -insecure`
app-misc/c_rehash-1.7-r1 | ``
dev-libs/openssl-1.0.2p-r1 | `asm sslv3 tls-heartbeat zlib -bindist -gmp -kerberos -rfc3779 -sctp -sslv2 -static-libs -test -vanilla`
sys-apps/debianutils-4.8.3 | `-static`
sys-libs/zlib-1.2.11-r2 | `-minizip -static-libs`
**FROM kubler/s6** |
app-admin/entr-4.1 | `-test`
dev-lang/execline-2.5.0.1 | `-static -static-libs`
dev-libs/skalibs-2.7.0.0 | `-doc -ipv6 -static-libs`
sys-apps/s6-2.7.2.1 | `-static -static-libs`
**FROM kubler/glibc** |
sys-apps/gentoo-functions-0.12 | ``
sys-libs/glibc-2.27-r6 | `hardened multiarch -audit -caps (-compile-locales) -doc -gd -headers-only (-multilib) -nscd (-profile) (-selinux) -suid -systemtap (-vanilla)`
sys-libs/timezone-data-2018g | `nls -leaps`
**FROM kubler/busybox** |
sys-apps/busybox-1.29.0 | `make-symlinks static -debug -ipv6 -livecd -math -mdev -pam -savedconfig (-selinux) -sep-usr -syslog -systemd`
#### Purged
- [x] Headers
- [x] Static Libs
