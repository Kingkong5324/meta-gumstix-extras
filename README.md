Yocto layer for images and extra recipes for Gumstix products.

This repository is developed in the environment provided by the
[Gumstix Yocto manifest][yocto-manifest] repository.  New code is
developed on the *next* branch corresponding to the *dev* branch of the
manifest and, when appropriate, merged back into the current release
branch called out by the *master* branch of the manifest. Older
releases are tagged by name in the manifest repository and use the
release-specific branches found in this repository.

This repository is discussed on the [Gumstix Mailing List][mailing-list]
and feature-requests/issues can be raised against the top-level
[manifest][yocto-manifest] project.

[yocto-manifest]: https://github.com/gumstix/yocto-manifest
[mailing-list]: https://lists.sourceforge.net/lists/listinfo/gumstix-users

This layer depends on:

URI: git://git.yoctoproject.org/poky.git
branch: dizzy
revision: HEAD

URI: git://git.openembedded.org/meta-openembedded.git
branch: dizzy
revision: HEAD

URI: git://github.com/gumstix/meta-gumstix.git
branch: dizzy
revision: HEAD

URI: git://github.com/bmwcarit/meta-ros.git
branch: master
revision: HEAD

URI: git://git.yoctoproject.org/meta-ti.git
branch: master
revision: HEAD

Layer maintainer: Adam Lee <adam@gumstix.com> for Gumstix, Inc.
