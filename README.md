### Build

[![](https://travis-ci.org/our-source/debian-mail-overlay.svg?branch=master)](https://travis-ci.org/our-source/debian-mail-overlay) [![](https://images.microbadger.com/badges/version/oursource/debian-mail-overlay:latest.svg)](https://microbadger.com/images/oursource/debian-mail-overlay:latest)

### Docker image

[![](https://images.microbadger.com/badges/image/oursource/debian-mail-overlay:latest.svg)](https://microbadger.com/images/oursource/debian-mail-overlay:latest) [![](https://img.shields.io/docker/automated/oursource/debian-mail-overlay.svg)](https://hub.docker.com/r/oursource/debian-mail-overlay/builds/) [![](https://img.shields.io/docker/pulls/oursource/debian-mail-overlay.svg)](https://hub.docker.com/r/oursource/debian-mail-overlay/) [![](https://img.shields.io/docker/stars/oursource/debian-mail-overlay.svg)](https://hub.docker.com/r/oursource/debian-mail-overlay/)

## our-source/debian-mail-overlay

This overlay base image contains Debian 10 "Buster" slim (remove some extra files that are normally not necessary within containers, such as man pages and documentation), compile skarnet.org's small & secure supervision software suite (skalibs, execline, s6) and build Rspamd, the fast, free and open-source spam filtering system.

Software built from source :

* Skalibs 2.9.3.0 : <https://skarnet.org/software/skalibs/>
* Execline 2.6.1.1 : <https://skarnet.org/software/execline/>
* s6 2.9.2.0 : <https://skarnet.org/software/s6/>
* Rspamd 2.6 : <https://rspamd.com/>
* Gucci 1.2.2 : <https://github.com/noqcks/gucci/>

Please see the [main repository](https://github.com/our-source/mailserver) for instructions.
