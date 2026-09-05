# Pocketblue extra

This repo provides some extra images with different wayland compositors for Pocketblue.
To switch to any of these images you should already have Pocketblue installed on your device.

Before switching, you should run `rpm-ostree reset` (alternatively, use the `sudo rpm-ostree rebase ostree-unverified-registry:<IMAGE>` command)

### Nothing Phone 1

- `sudo bootc switch quay.io/pocketblue-extra/nothing-spacewar-niri:44`
- `sudo bootc switch quay.io/pocketblue-extra/nothing-spacewar-sway:44`
- `sudo bootc switch quay.io/pocketblue-extra/nothing-spacewar-cosmic:44`

### OnePlus 6/6T and Xiaomi Poco F1

- `sudo bootc switch quay.io/pocketblue-extra/qualcomm-sdm845-niri:44`
- `sudo bootc switch quay.io/pocketblue-extra/qualcomm-sdm845-sway:44`
- `sudo bootc switch quay.io/pocketblue-extra/qualcomm-sdm845-cosmic:44`

### Xiaomi Pad 5

- `sudo bootc switch quay.io/pocketblue-extra/xiaomi-nabu-niri:44`
- `sudo bootc switch quay.io/pocketblue-extra/xiaomi-nabu-sway:44`
- `sudo bootc switch quay.io/pocketblue-extra/xiaomi-nabu-cosmic:44`

Or, if you have a UFS that requires a patched kernel:

- `sudo bootc switch quay.io/pocketblue-extra/xiaomi-nabu-niri:44-rodriguezst`
- `sudo bootc switch quay.io/pocketblue-extra/xiaomi-nabu-sway:44-rodriguezst`
- `sudo bootc switch quay.io/pocketblue-extra/xiaomi-nabu-cosmic:44-rodriguezst`

### Xiaomi Pad 6

- `sudo bootc switch quay.io/pocketblue-extra/xiaomi-pipa-niri:44`
- `sudo bootc switch quay.io/pocketblue-extra/xiaomi-pipa-sway:44`
- `sudo bootc switch quay.io/pocketblue-extra/xiaomi-pipa-cosmic:44`

