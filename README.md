## hardware/debian-mail-overlay

This overlay base image contains Debian Stretch slim (remove some extra files that are normally not necessary within containers, such as man pages and documentation), compile skarnet.org's small & secure supervision software suite (skalibs, execline, s6) and build Rspamd, the fast, free and open-source spam filtering system.

Software built from source :

* Skalibs 2.6.4.0 : https://skarnet.org/software/skalibs/
* Execline 2.5.0.0 : https://skarnet.org/software/execline/
* s6 2.7.1.1 : https://skarnet.org/software/s6/
* Rspamd 1.8.0 : https://rspamd.com/
* Gucci 0.0.4 : https://github.com/noqcks/gucci/

Please see the [main repository](https://github.com/hardware/mailserver) for instructions.
