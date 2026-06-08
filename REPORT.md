# Лабораторная работа №0
## Изучение систем обмена данными

**Студент:** Семендяй Аглая  
**Дата:** 13.05.2026  

```bash
aglaya@debian ~> openssl version
OpenSSL 3.5.4 30 Sep 2025 (Library: OpenSSL 3.5.4 30 Sep 2025)

aglaya@debian ~> cmake --version
cmake version 3.31.6

CMake suite maintained and supported by Kitware (kitware.com/cmake).

aglaya@debian ~> curl --version
curl 8.14.1 (x86_64-pc-linux-gnu) libcurl/8.14.1 OpenSSL/3.5.4 zlib/1.3.1 brotli/1.1.0 zstd/1.5.7 libidn2/2.3.8 libpsl/0.21.2 libssh2/1.11.1 nghttp2/1.64.0 nghttp2/1.8.0 librtmp/2.3 OpenLDAP/2.6.10
Release-Date: 2025-06-04, security patched: 8.14.1-2+deb13u2
Protocols: dict file ftp ftps gopher gophers http https imap imaps ipfs ipns ldap ldaps mqtt pop3 pop3s rtmp rtsp scp sftp smb smbs smtp smtps telnet tftp ws wss
Features: alt-svc AsynchDNS brotli GSS-API HSTS HTTP2 HTTP3 HTTPS-proxy IDN IPv6 Kerberos Largefile libz NTLM PSL SPNEGO SSL threadsafe TLS-SRP UnixSockets zstd

aglaya@debian ~> git --version
git version 2.47.3

aglaya@debian ~> g++ --version
g++ (Debian 14.2.0-19) 14.2.0
Copyright (C) 2024 Free Software Foundation, Inc.
This is free software; see the source for copying conditions. There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

aglaya@debian ~> hub --version
git version 2.47.3
hub version 2.14.2

aglaya@debian ~> make --version
GNU Make 4.4.1
Built for x86_64-pc-linux-gnu
Copyright (C) 1988-2023 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <https://gnu.org/licenses/gpl.html>
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

aglaya@debian ~> subl --version
Sublime Text Build 4200

aglaya@debian ~> tree --version
tree v2.2.1 © 1996 - 2024 by Steve Baker, Thomas Moore, Francesc Rocher, Florian Sesser, Kyosuke Tokoro

aglaya@debian ~> wget --version
GNU Wget 1.25.0 built on linux-gnu.

-cares +digest -gpgme +https +ipv6 +iri +large-file -metalink +nls +ntlm +opie +psl +ssl/gnutls

Wgetrc: /etc/wgetrc (system)
Locale: /usr/share/locale
Compile: gcc -DHAVE_CONFIG_H -DSYSTEM_WGETRC="/etc/wgetrc" -DLOCALEDIR="/usr/share/locale" -I. -I../src -I../lib -I../lib -Wdate-time -D_FORTIFY_SOURCE=2 -I/usr/include/p11-kit-1 -DHAVE_LIBGNUTLS -DNDEBUG -g -O2 -Werror=implicit-function-declaration -ffile-prefix-map=/build/reproducible-path/wget-1.25.0=. -fstack-protector-strong -fstack-clash-protection -Wformat -Werror=format-security -fcf-protection -DNO_SSLv2
Link: gcc -I/usr/include/p11-kit-1 -DHAVE_LIBGNUTLS -DNDEBUG -g -O2 -Werror=implicit-function-declaration -ffile-prefix-map=/build/reproducible-path/wget-1.25.0=. -fstack-protector-strong -fstack-clash-protection -Wformat -Werror=format-security -fcf-protection -DNO_SSLv2 -Wl,-z,relro -Wl,-z,now -lpcre2-8 -luuid -lidn2 -lnettle -lgnutls -lz -lpsl ../lib/libgnu.a

Copyright (C) 2015 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <http://www.gnu.org/licenses/gpl.html>.
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

Originally written by Hrvoje Niksic <hniksic@xemacs.org>.
Please send bug reports and questions to <bug-wget@gnu.org>.
