Raspberry Pi 3.5.7 Xenomai patch
===============

This patch should be applied AFTER the corresponding I-pipe patch.

We included a Buildroot configuration. This configuration downloads the correct kernel version, the correct Xenomai patch, the correct Raspberry Pi patches and applies them in the correct order.

Instruction on how to install here: http://goo.gl/WKkOv

This patch is based on the work of Paul[1] and fixed by me for cleanly applying.

Brought to you by http://idea-on-line.it !

[1] http://www.xenomai.org/pipermail/xenomai/2013-February/027752.html
