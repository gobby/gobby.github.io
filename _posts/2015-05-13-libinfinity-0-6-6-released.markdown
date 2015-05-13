---
layout: post
title:  libinfinity 0.6.6 released
date:   2015-05-13 21:07:00 -0400
---

libinfinity 0.6.6 has been released. This is a bugfix release in the 0.6.x series. It fixes a problem where a server's certificate would silently be accepted even though it failed verification if no certificate pinning is performed, i.e. the hostname matches and its CA is trusted. A potential client-side crash is also fixed which occured when a server is shut down while still being connected. It is recommended that all users update to this new version of libinfinity.

libinfinity 0.6.6 can be [downloaded](https://github.com/gobby/gobby/wiki/Download)
from the Wiki page on GitHub.
