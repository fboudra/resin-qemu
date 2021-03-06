Change log
-----------

* Update tests/autohat - Fixes HOSTOS version parsing bug + Adds new tests [Praneeth]
* Update grub.cfg - Search QEMU root device by label instead of hda/sda/vda paths [Praneeth]
* Update linux-yocto_%.bbappend - To enable support for running the image on Google Cloud [Praneeth]

# v2.0.0-rc5.rev1 - 2017-03-26

* Update the meta-resin submodule to version v2.0.0-rc5 [Florin]
* Update tests/autohat - Bring in stability improvements and new tests [Praneeth]
* Increase size of the resin initramfs image from 8192K to 16384K to accommodate for size increase due to x86 arch [Florin]
* Update the meta-resin submodule to version v2.0.0-rc3 [Florin]

# v2.0.0-beta12.rev1 - 2017-02-27

* Bump tests/autohat to current HEAD [Andrei]
* Bump resin-yocto-scripts to current HEAD [Andrei]
* meta-resin: Bump to 2.0.0-beta12 [Andrei]

# v2.0.0-beta11.rev1 - 2017-02-15

* Update meta-resin to v2.0.0-beta.11 [Andrei]

# v2.0.0-beta10.rev1 - 2017-02-14

* Update meta-resin to v2.0.0-beta.10 [Andrei]

# v2.0.0-beta.9 - 2017-02-08

* Update meta-resin to v2.0-beta.9 [Andrei]

# v2.0.0-beta.8 - 2017-01-27

* Update meta-resin to v2.0-beta.8 [Andrei]
* Update resin-yocto-scripts to HEAD of the master branch [Florin]
* Update tests/start.sh - Enable AutoHaT support for Qemu 32 bit images [Horia]
* Update tests/autohat - Bring in stability improvements and new tests [Praneeth]

# v2.0.0-beta.7 - 2016-12-05

* Update meta-resin to v2.0-beta.7 [Florin]

# v2.0.0-beta.6 - 2016-12-05

* Update meta-resin to v2.0-beta.6 [Andrei]

# v2.0.0-beta.5 - 2016-11-30

* Update meta-resin to v2.0-beta.5 [Andrei]

# v2.0.0-beta.3 - 2016-11-07

* Update meta-resin to v2.0-beta.3 [Andrei]
* Cleanup docker-resin-supervisor-disk of unneeded variables [Andrei]
* Update resin-yocto-scripts to fix logging in container builds

# v2.0.0-beta.1 - 2016-10-11

* Update meta-resin to v2.0-beta.1 [Andrei]
* Add meta-filesystem as we need aufs-utils [Andrei]
* Add build support for resinos [Andrei]
* Update resin-yocto-script to include changes in our image types [Theodor]
* Replace the concept of a debug image with a development image [Theodor]
* Update meta-resin to include avahi [Florin]
* Update resin-yocto-scripts to include kernel headers handling as gzip [Florin]

# v1.16.0 - 2016-09-27

* Update meta-resin to v1.16 [Florin]

# v1.15.0 - 2016-09-24

* Update meta-resin to v1.15 [Florin]

# v1.14.0 - 2016-09-23

* Update meta-resin to v1.14 [Florin]

# v1.13.0 - 2016-09-23

* Update meta-resin to v1.13 [Florin]

# v1.12.0 - 2016-09-21

* Update meta-resin to v1.12 [Florin]
* Update resin-yocto-scripts to include resinhup upload to dockerhub [Florin]
* Update tests/autohat - Fetching the new resin-cli and adding additional tests [Praneeth]
* Update meta-resin [Florin]
* Change .coffee to announce partition 1 now holds config.json and also introduce versioning (v1) [Florin]

# v1.11.0 - 2016-08-31

* Update meta-resin to v1.11 [Florin]

# v1.10.0 - 2016-08-24

* Update meta-resin to v1.10 [Florin]

# v1.9.0 - 2016-08-24

* Update meta-resin to v1.9 [Florin]
* Update resin-yocto-scripts for including kernel modules headers deploy [Florin]

# v1.8.0 - 2016-08-02

* Bump meta-resin to v1.8 [Andrei]

# v1.7.2 - 2016-07-26

* Bump resin-yocto-scripts to current HEAD to include ability to run tests based on variable [Praneeth]

# v1.7.1 - 2016-07-26

* No more debug images in staging

# v1.7.0 - 2016-07-14

* Update meta-resin to v1.7
* Add support for qemux86 and qemux86-64 [Andrei]
