Recovery Device Tree for the Samsung Galaxy M30s mangled to theoretically work on M21
How-to compile it:

To build:

. build/envsetup.sh
export ALLOW_MISSING_DEPENDENCIES=TRUE
lunch omni_REL-eng
make recoveryimage

While the TWRP tree for this device exists, the TWRP recovery doesn't yet support ROMs with super.img, so it won't boot even after being signed.
