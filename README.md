manifests to build Android 4.3 for Xiaomi Mi2/2S/2A.

How to build MI2/2S:
-------------

Initialize repo:

    repo init -u git://github.com/mitwo-dev/platform_manifest
    repo sync

    . build/envsetup.sh && lunch aries-userdebug

    make otapackage -j16



How to build MI2A:
------------

Initialize repo:
 
    repo init -u git://github.com/mitwo-dev/platform_manifest
    repo sync
    
    . build/envsetup.sh && lunch taurus-userdebug

    make otapackage -j16
