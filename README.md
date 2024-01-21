# Kernel manifest for Nothing Phone 2 #

## Repo Init ##
```bash
repo init -u https://github.com/aospa-pong/kernel_manifest.git -b android-msm-phone2-5.10-android12
```
## Sync Source ##
```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)
```
## Building Kernel ##
```bash
BUILD_KERNEL=1 ./build_ai2202.sh
```
### Submitting Patches ###
Please refer to this for submitting patches: https://github.com/AOSPA/manifest#submitting-patches
