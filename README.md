# lineageos-samsungd2xxx
Proprietary blobs and local manifests for Samsung d2xxx (Samsung Galaxy S III) devices.

The manifests here work for the following devices:

- d2tmo
- d2att
- d2vzw
- d2spr

d2lte/unified is NOT supported due to the de-unifying of builds beginning with CM/Lineage 12.

If you're compiling builds on a remote machine (VPS, dedicated, etc.), this is for you, since you can't easily extract blobs to a remote machine, and most personal machines aren't suitable for building due to lack of a decent internet connection.

File should be placed in /root/android/.repo/local_manifests. If .repo doesn't exist, you need to run build/envsetup.sh.

Official development: http://forum.xda-developers.com/galaxy-s3-t-mobile/development/rom-cyanogenmod-12-t-mobile-samsung-t3055048
