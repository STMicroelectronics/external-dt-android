# external-dt #

This module provides the device trees for the STM32MP25 DK and EVAL boards.
It is part of the STMicroelectronics delivery for Android.

## Description ##

This module targets STM32MP25 in OpenSTDroid v6.2.0.
Please see the release notes for more details.

## Documentation ##

* The [release notes][] provide information on the release.
[release notes]: https://wiki.st.com/stm32mpu/wiki/STM32_MPU_OpenSTDroid_release_note_-_v6.2.0

## Dependencies ##

This module cannot be used alone. It is part of the STMicroelectronics delivery for Android.

## Contents ##

This module contains several files and directories (build scripts are part of the OpenSTDroid distribution).
* `./linux/*`: device tree used for Linux (built using the build_kernel script)
* `./mcuboot/*`: device tree used for MCUboot (built with TF-M source using the build_system script)
* `./tfa/*`: device tree used for TF-A firmware (built with TF-A source using the build_bootloader script)
* `./tfm/*`: device tree used for TF-M (built with TF-M source using the build_system script)
* `./uboot/*`: device tree used for U-Boot (built with U-Boot source using the build_bootloader script)
