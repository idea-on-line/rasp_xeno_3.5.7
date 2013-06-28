RaspberryPI 3.5.7 Xenomai patch
===============

This patch should be applied AFTER the corresponding I-pipe patch.

We included a Buildroot configuration. This configuration downloads the correct kernel, the correct Xenomai patch, the correct RaspberryPI patch and applies them in the correct order.

Instruction on how to install here: http://goo.gl/WKkOv

This patch is based on the work of Paul[1] and fixed for applying cleanly.

[1] http://www.xenomai.org/pipermail/xenomai/2013-February/027752.html
