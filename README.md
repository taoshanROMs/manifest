[Android Open Kang Project](http://aokp.co)
====================================


Download the Source
===================

Please read the [AOSP building instructions](http://source.android.com/source/index.html) before proceeding.

Initializing Repository
-----------------------

Init repo :

    $ repo init -u https://github.com/taoshanROMs/manifest.git -b aokp-4.4


Sync repo :

    $ repo sync

***

Building
--------

After the sync is finished, please read the [instructions from the Android site](http://s.android.com/source/building.html) on how to build.

    . build/envsetup.sh
    brunch taoshan


You can also build (and see how long it took) for specific devices like this:

    . build/envsetup.sh
    time brunch aokp_taoshan-userdebug

Remember to `make clobber` every now and then!
