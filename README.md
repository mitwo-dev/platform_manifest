manifests to build Android 4.3 for Xiaomi Mi2.

How to build:
-------------

Initialize repo:

    repo init -u git://github.com/mitwo-dev/platform_manifest
    repo sync

    . build/envsetup.sh && lunch

    Choose aries-userdebug

    make otapackage -j16
