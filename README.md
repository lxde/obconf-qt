# ObConf-Qt

## Overview

ObConf-Qt is a Qt port of [ObConf](http://openbox.org/wiki/ObConf:About), a configuration editor for window manager [OpenBox](http://openbox.org).   

It is maintained by the LXQt project but can be used independently from this desktop environment.   

## Installation

### Compiling source code

Runtime dependencies are Qt X11 Extras, gtk-update-icon-cache, hicolor-icon-theme and Openbox.   
Additional build dependencies are CMake and [liblxqt](https://github.com/lxqt/liblxqt), optionally Git to pull latest VCS checkouts.

Code configuration is handled by CMake. CMake variable `CMAKE_INSTALL_PREFIX` has to be set to `/usr` on most operating systems.   

To build run `make`, to install `make install` which accepts variable `DESTDIR` as usual.   

### Binary packages

Official binary packages are available in Arch Linux and Debian (as of Debian stretch).   
The tool is missing in Fedora so far. Same applies to openSUSE where it is about to be included, though.   

### Translations

Translations can be done in [LXQt-Weblate](https://translate.lxqt-project.org/projects/lxqt-configuration/obconf-qt/).

<a href="https://translate.lxqt-project.org/projects/lxqt-configuration/obconf-qt/">
<img src="https://translate.lxqt-project.org/widgets/lxqt-configuration/-/obconf-qt/multi-auto.svg" alt="Translation status" />
</a>
