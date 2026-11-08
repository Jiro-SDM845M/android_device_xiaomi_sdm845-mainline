# Common Xiaomi SDM845 Device Tree for LineageOS Mainline

This repository contains the common device tree configurations for Qualcomm Snapdragon 845 (SDM845) Xiaomi devices on LineageOS Mainline (Linux 6.x / 7.x).

## Supported Devices
- POCO F1 (`beryllium`)
- Mi MIX 2S (`polaris`)
- Mi 8 (`dipper`)
- Mi MIX 3 (`perseus`)

## Architecture
- Inherits from `device/mainline/qcom-common` (`soc/sdm845`).
- Configures dynamic Super partitions (`system` + `vendor` + `cust` -> ~5.1GB).
- Upstream Linux audio, display, and remoteproc initialization.
