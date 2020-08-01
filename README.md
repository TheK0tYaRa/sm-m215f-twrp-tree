## Recovery Device Tree for the Samsung Galaxy M30s mangled to theoretically work on M21

## How-to compile it:

To build:

```sh
. build/envsetup.sh
export ALLOW_MISSING_DEPENDENCIES
lunch omni_REL-eng
make recoveryimage
