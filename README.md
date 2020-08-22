# Twice OS #

Credits
-------
* [**PixelExperience**](https://github.com/PixelExperience)
* [**LineageOS**](https://github.com/LineageOS)
* [**KomodoOS**](https://github.com/Komodo-OS-Rom)
* [**ArrowOS**](https://github.com/ArrowOS)
* [**AOSiP**](https://github.com/AOSiP)

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/TwiceOS/manifest -b ten

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch twice_$device-userdebug

# Build the code
$ mka bacon -jX
```
