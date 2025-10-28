# Custom Recovery Device Tree for Samsung Galaxy S23 Base (dm1q)
## Shared with Samsung SM8550 common tree:
```bash
https://github.com/cola2261/android_device_samsung_sm8550-common-recovery
```

## To build: 
```bash
. build/envsetup.sh
lunch twrp_dm1q-eng
mka recoveryimage -j$(nproc --all)
```
