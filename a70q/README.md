## Firmware Info

- Device: Samsung Galaxy A70
- Region: XXV (Vietnam)
- Version: `A705FXXU5DXD2` / `BOOT.XF.3.1-00270-SM6150LZB-1`

## Patches / Fixes

### ButtonsDxe:

- Reason: Helps navigating Menus (e.g. UEFI Menu).
- Patch Nr. 1: Key code was patched for the power button to be mapped as ENTER instead of Special Samsung Keycode.
- Patch Creator: [Robotix22](https://github.com/Robotix22)`

### ClockDxe:

- Reason: To be able to boot Windows with debug build.
- Patch: Low Power Mode handler registration has been patched so it does not register LPM mode
- Patch Creator: [N1kroks](https://github.com/N1kroks)

### UsbConfigDxe:

- **Reason:** Usefull for Navigating UEFI and the OSs.
- **Patch:** A Check for Platform CLS was Patched to Check for IDP instead.
- **Patch Creator:** [Robotix22](https://github.com/Robotix22)
