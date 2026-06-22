# TWRP Device Tree for the Samsung Galaxy A50s (a50sxx)

The Galaxy A50s (codenamed _"a50sxx"_) is an upper-mid-range smartphone from Samsung.

It was announced and released in September 2019.

## Device specifications


| Feature | Specification |
| ---------------------------: | :----------------------------------------------------------------------------- |
| Chipset | Exynos 9611 |
| CPU | Octa-core (4x2.3 GHz Cortex-A73 & 4x1.7 GHz Cortex-A53) |
| GPU | Mali-G72 MP3 |
| Memory | 4GB / 6GB RAM (LPDDR4X) |
| Shipped OS | Android 9.0 Pie (One UI 1.5) |
| Storage | 64GB / 128GB (UFS 2.1) |
| SIM | Single SIM (Nano-SIM) or Dual SIM (Nano-SIM, dual stand-by) |
| MicroSD | Up to 512GB (Dedicated Slot) |
| Battery | 4000mAh Li-Po (non-removable), 15W fast charge |
| Dimensions | 158.5 x 74.5 x 7.7 mm (6.24 x 2.93 x 0.30 in) |
| Display | 6.4", 1080 x 2340 pixels, 19.5:9 ratio, Super AMOLED, 60Hz (~403 ppi density) |
| Rear Camera 1 (Sony IMX582) | 48 MP, f/2.0, 26mm (wide), 1/2.0", 0.8µm, PDAF |
| Rear Camera 2 (Samsung S5K4HA)| 8 MP, f/2.2, 13mm (ultrawide), 1/4.0", 1.12µm |
| Rear Camera 3 (GalaxyCore) | 5 MP, f/2.2, (depth) |
| Front Camera (Sony IMX616) | 32 MP, f/2.0, 25mm (wide), 1/2.8", 0.8µm |
| Fingerprint | Under display, optical |
| Sensors | Accelerometer, Gyro, Proximity, Compass, Hall IC |
| Extras | Single bottom-firing speaker, NFC, FM Radio, 3.5mm jack |

## Device picture

<img src="https://github.com/user-attachments/assets/21d586d6-793a-4ae0-b6fd-fc725cea11b6" />"/>

## Kernel source

Available at [FreshROMs/android_kernel_samsung_exynos9610_mint](https://github.com/FreshROMs/android_kernel_samsung_exynos9610_mint)

## How to build

This device tree was tested and is fully compatible with [minimal-manifest-twrp](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp).

1. Set up the build environment following the instructions [here](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp/blob/twrp-12.1/README.md#getting-started)

2. In the root folder of the fetched repo, clone the device tree:

```bash
git clone https://github.com/Bryxian/android_device_samsung_a50s -b twrp-12.1 device/samsung/a50sxx
```

3. To build:

```bash
. build/envsetup.sh
lunch twrp_a50sxx-eng
mka recoveryimage
```

## Copyright

```
#
# Copyright (C) 2024 The TWRP Open Source Project
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#
```
