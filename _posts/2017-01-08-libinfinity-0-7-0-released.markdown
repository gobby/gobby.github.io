---
layout: post
title:  libinfinity 0.7.0 released
date:   2017-01-08 15:40:00 -0800
---

libinfinity 0.7.0 has been released. The primary new feature is support for
gobject-introspection, which allows using the libinfinity API from
higher-level programming languages such as Python. Furthermore, situations
were a disconnect happens silently are now recognized much faster due to usage
of TCP keepalive probes. Also, the infinoted server allows to listen on only a
specific network interface. Support for GTK+ 2.x has been dropped, GTK+ 3.x
is the only supported GTK+ version now.

There is no version of Gobby yet which makes use of libinfinity 0.7.0, however
the standalone server, infinoted 0.7.0, can be operated with the current
release of Gobby, Gobby 0.5.0.

libinfinity 0.7.0 can be [downloaded](https://github.com/gobby/gobby/wiki/Download)
from the Wiki page on GitHub.
