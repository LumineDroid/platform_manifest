## **Getting Started** ##

**To initialize your local repository using the LumineDroid , use a command like this** :

```bash
repo init -u https://github.com/LumineDroid/platform_manifest -b camellia --git-lfs
```

**And then sync up** :

```bash
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```

## Building

```bash

$ . build/envsetup.sh
$ lunch $device-cp2a-userdebug
$ mka bacon
```
#
