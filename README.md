# Pocketblue extra

This repo provides some extra images with different wayland compositors for Pocketblue.
To switch to any of these images you should already have Pocketblue installed on your device.

Before switching, you should run `rpm-ostree reset` (alternatively, use the `sudo rpm-ostree rebase ostree-unverified-registry:<IMAGE>` command)

### Nothing Phone 1

- `sudo bootc switch quay.io/pocketblue-extra/nothing-spacewar-niri:43`
- `sudo bootc switch quay.io/pocketblue-extra/nothing-spacewar-sway:43`
- `sudo bootc switch quay.io/pocketblue-extra/nothing-spacewar-cosmic:43`

### OnePlus 6/6T and Xiaomi Poco F1

- `sudo bootc switch quay.io/pocketblue-extra/qualcomm-sdm845-niri:43`
- `sudo bootc switch quay.io/pocketblue-extra/qualcomm-sdm845-sway:43`
- `sudo bootc switch quay.io/pocketblue-extra/qualcomm-sdm845-cosmic:43`

### Xiaomi Pad 5

- `sudo bootc switch quay.io/pocketblue-extra/xiaomi-nabu-niri:43`
- `sudo bootc switch quay.io/pocketblue-extra/xiaomi-nabu-sway:43`
- `sudo bootc switch quay.io/pocketblue-extra/xiaomi-nabu-cosmic:43`

### Xiaomi Pad 6

- `sudo bootc switch quay.io/pocketblue-extra/xiaomi-pipa-niri:43`
- `sudo bootc switch quay.io/pocketblue-extra/xiaomi-pipa-sway:43`
- `sudo bootc switch quay.io/pocketblue-extra/xiaomi-pipa-cosmic:43`

