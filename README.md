Collection of my most relevant projects, in no particular order.

# Reverse Engineering

## Extron IP Link drivers
Reverse engineering on the file format used by Extron IP Link drivers.

Details of the format are in a [dedicated wiki](https://github.com/rapperskull/extron-documentation/wiki) and a tool to unpack and repack drivers is available on [GitHub](https://github.com/rapperskull/extron-pkg).

# Samsung TV

## Set TV time from NTP server
Allows the TV to automatically set its clock on startup using NTP for both Linux and exeDSP.

More information is available on the [SamyGO Forum](https://forum.samygo.tv/viewtopic.php?t=13859) and [GitHub](https://github.com/rapperskull/Samsung_libsetTVTime).

## Fix for 288p resolution support
The parameters required for 288p support on C-series Samsung TVs were incorrect. Samsung likely never bothered to support this resolution, especially over HDMI. This SamyGOso library fixes that.

More information is available on the [SamyGO Forum](https://forum.samygo.tv/viewtopic.php?t=13857) and [GitHub](https://github.com/rapperskull/Samsung_288p_support).

# Retro Gaming

## extract-xiso rewrite
Substantial rewrite of a tool to extract and convert OG Xbox disc images. The original code has been modernized while keeping C99 compatibility, simplified, and improved with new features and better maintainability.

More information is available on [GitHub](https://github.com/rapperskull/extract-xiso/tree/devel).

# Android

## Realme GT 2 Pro EU bootloader unlock
Adaptation of the Dirty Pipe Linux vulnerability to spoof the phone model Android property and allow bootloader unlock using official methods.

More information is available on [XDA Forums](https://xdaforums.com/t/eu-model-unlock-bootloader-of-european-model.4454787/).

## libnvbk
A library to manipulate NVBK files found on OPPO/Realme/OnePlus devices. Written to support [realme GPS L5 Enabler](#realme GPS L5 Enabler), it only implements the functions needed by it.\
The repository also documents the NVBK file format, by means of reverse engineering.

Available on [GitHub](https://github.com/rapperskull/libnvbk).

## realme GPS L5 Enabler
Magisk module to enable L5/E5a/B2a GPS bands on realme/OPPO/OnePlus devices with Qualcomm Snapdragon processors.\
I found out that the Chinese variant of my phone supported more GPS bands, despite having the same hardware. This started the jorney that led me to [libnvbk](#libnvbk) and this module.

More information is available on [XDA Forums](https://xdaforums.com/t/mod-enable-gps-l5-e5a-b2a-bands-on-global-eu-model-rmx3301.4587471/) and [GitHub](https://github.com/rapperskull/realme_gps_l5_enabler).
