# Docker Images for KubeBerry Project

## KubeBerry Project

## Docker Images
 
All images of the project are based on [arm32v7/alpine:3.10](https://hub.docker.com/r/arm32v7/alpine).

---

### Ansible

based on

---

### Perl5

Content:

* Perl 5
* [CPAN Minus](https://metacpan.org/pod/distribution/App-cpanminus/lib/App/cpanminus/fatscript.pm)

```shell
docker run -it kubeberry/perl5 perl --version

This is perl 5, version 28, subversion 2 (v5.28.2) built for armv8l-linux-thread-multi

Copyright 1987-2019, Larry Wall

Perl may be copied only under the terms of either the Artistic License or the
GNU General Public License, which may be found in the Perl 5 source kit.

Complete documentation for Perl, including FAQ lists, should be found on
this system using "man perl" or "perldoc perl".  If you have access to the
Internet, point your browser at http://www.perl.org/, the Perl Home Page.
```

---

### Perl5 Mojolicious

Based on `kubeberry/perl5` image.

Content:

* [Mojolicious](https://metacpan.org/pod/Mojolicious)

```shell
docker run -it kubeberry/perl5-mojolicious mojo version
CORE
  Perl        (v5.28.2, linux)
  Mojolicious (8.23, Supervillain)

OPTIONAL
  Cpanel::JSON::XS 4.09+  (n/a)
  EV 4.0+                 (n/a)
  IO::Socket::Socks 0.64+ (n/a)
  IO::Socket::SSL 2.009+  (n/a)
  Net::DNS::Native 0.15+  (n/a)
  Role::Tiny 2.000001+    (n/a)

This version is up to date, have fun!
```

---

### Python2

---

### Python3