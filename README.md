openelec-xboxdrv
================

Binary driver for xboxdrv.

The idea of this is to provide a plugin that can be applied to any homebrew build of OpenElec to provide drivers for the Xbox game controller.

This build possibly won't be maintained as I don't own one of these controllers, yet hope that somebody out there has a need for and is willing to fork/maintain this code.

Usage
-----

* Change to your OpenElec.TV/packages/tools directory.
* Clone this repository to a 'xboxdrv' directory.
* Change to your OpenElec.TV source directory.
* PROJECT=<PROJECT> ARCH=<ARCHITECT> ./scripts/build xboxdrv
 * example: PROJECT=Intel ARCH=x86_64 ./scripts/build xboxdrv
