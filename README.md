### Build

[![](https://travis-ci.org/our-source/debian-mail-overlay.svg?branch=master)](https://travis-ci.org/our-source/debian-mail-overlay) [![](https://images.microbadger.com/badges/version/oursource/debian-mail-overlay:latest.svg)](https://microbadger.com/images/oursource/debian-mail-overlay:latest)

### Docker image

[![](https://images.microbadger.com/badges/image/oursource/debian-mail-overlay:latest.svg)](https://microbadger.com/images/oursource/debian-mail-overlay:latest) [![](https://img.shields.io/docker/automated/oursource/debian-mail-overlay.svg)](https://hub.docker.com/r/oursource/debian-mail-overlay/builds/) [![](https://img.shields.io/docker/pulls/oursource/debian-mail-overlay.svg)](https://hub.docker.com/r/oursource/debian-mail-overlay/) [![](https://img.shields.io/docker/stars/oursource/debian-mail-overlay.svg)](https://hub.docker.com/r/oursource/debian-mail-overlay/)

## our-source/debian-mail-overlay

This overlay base image contains Debian 10 "Buster" slim (remove some extra files that are normally not necessary within containers, such as man pages and documentation), compile skarnet.org's small & secure supervision software suite (skalibs, execline, s6) and build Rspamd, the fast, free and open-source spam filtering system.

Software built from source :

* Skalibs 2.8.1.0 : https://skarnet.org/software/skalibs/
* Execline 2.5.1.0 : https://skarnet.org/software/execline/
* s6 2.8.0.1 : https://skarnet.org/software/s6/
* Rspamd 1.9.4 : https://rspamd.com/
* Gucci 0.1.0 : https://github.com/noqcks/gucci/

Please see the [main repository](https://github.com/our-source/mailserver) for instructions.
