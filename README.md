# OrangeFox Device Tree for Samsung Galaxy Note 10+ (d2s)

## How to build

This device tree was tested and is fully compatible with [minimal-manifest-twrp](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp).

1. Set up the build environment following the instructions [here](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp/blob/twrp-11/README.md#getting-started)

2. In the root folder of the fetched repo, clone the device tree:

```bash
git clone https://github.com/ByteKnight-glitch/EternityOF.git -b d2s device/samsung/d2s
```

3. To build:

```bash
. build/envsetup.sh
lunch twrp_d2s-eng
mka recoveryimage
```



## Attribution
This device tree is based on the Eternity TWRP which is based on the TWRP Open Source Project and has been modified for the Samsung Galaxy Note 10+ (`d2s`).


## Copyright

```
#
# Copyright (C) 2024 The OrangeFox Recovery Project
# Portions Copyright (C) 2024 The TWRP Open Source Project
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing,
# software distributed under the License is distributed on an
# "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
# either express or implied. See the License for the specific
# language governing permissions and limitations under the License.
#
```
