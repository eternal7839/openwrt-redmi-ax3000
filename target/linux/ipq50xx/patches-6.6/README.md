# IPQ50XX Kernel Patches for Linux 6.6

This directory contains patches that are still needed for Linux 6.6.

## Patches removed (already in Linux 6.6 or no longer needed):

### Clock/GCC patches (removed - in 6.6):
- 032-08-clk-qcom-clk-rcg2-add-rcg2-mux-ops.patch
- 032-09-clk-qcom-apss-ipq6018-fix-apcs_alias0_clk_src.patch
- 032-11-clk-qcom-apss-ipq-pll-use-OF-match-data-for-Alpha-PL.patch
- 301-clk-qcom-clk-alpha-pll-Add-support-for-Stromer-PLLs.patch
- 302-dt-bindings-arm64-ipq5018-Add-binding-descriptions-f.patch
- 303-clk-qcom-Add-Global-Clock-controller-GCC-driver-for-.patch
- 304-dt-bindings-pinctrl-qcom-Add-ipq5018-pinctrl-binding.patch
- 305-pinctrl-qcom-Add-IPQ5018-pinctrl-driver.patch
- 306-arm64-dts-Add-ipq5018-SoC-and-MP03-board-support.patch
- 307-arm64-defconfig-Enable-IPQ5018-SoC-base-configs.patch
- 311-arm64-dts-qcom-ipq5018-Add-scm-node.patch
- 312-arm64-Kconfig-enable-qcom-scm.patch
- 321-firmware-qcom_scm-Disable-SDI.patch
- 322-arm64-dts-qcom-ipq5018-set-download-mode.patch
- 331-ARM-mach-qcom-Add-support-for-IPQ50xx.patch
- 332-arm-dts-qcom-Add-ipq5018-support.patch
- 341-gcc-ipq5018-fix-reset-issue-for-uniphy-and-gephy.patch
- 351-clk-qcom-support-for-duplicate-freq-in-RCG2-freq-tab.patch
- 371-clk-qcom-ipq5018-remove-clk_ignore_unused-from-boota.patch
- 381-clk-qcom-apss-ipq-pll-refactor-the-driver-to-accommo.patch
- 382-clk-qcom-apss-ipq-pll-add-support-for-IPQ5018.patch
- 383-mailbox-qcom-Add-ipq5018-apcs-compatible.patch
- 384-arm64-dts-qcom-ipq5018-Add-APSS-mailbox-and-clock-no.patch

### Remaining patches to be evaluated:
- 401-421: NAND/MTD patches (likely still needed)
- 701-703: Network/MDIO patches (likely still needed)
- 801-824: Remoteproc/WiFi patches (likely still needed)

## Notes:
Linux 6.6 has much better IPQ5018 support than 5.15.
Many patches from 5.15 have been upstreamed.
