### This repisotory is for distribution purposes

### Updates V1.5.30 - 08/30/2019
- BLE server library fix: package with dependencies
- Bug: fails to install vc_redist.x64.exe on some computer

### Updates V1.5.29 - 08/20/2019
- init cmd & functions to get generic and custom item
- windows: fix BLEServer.exe

### Updates V1.5.28 - 08/13/2019
- init auto-updater
- init elliptic (encryption lib)

### Updates V1.5.27 - 08/08/2019
- BLE server library fix: ability to get advertisement manufacturer data
- Consume manual cmd packet (C2H: Manual Fills)
- Init new features: abilty to store custom item into a Ethernom's device

### Updates V1.5.26 - 07/25/2019
- fix notification queue problem
- only send string[0] up to string[31] if device name string.length is more than 31
- init password change features

### Updates V1.5.25 - 07/24/2019
- Auto connect to last connected device

### Updates V1.5.24 - 07/22/2019
- Init create storage directory
- Ability to remember connected device
- Allow 1 remembered device to init auto connect
- Scan nearby BLE device no longer prompt to front when discover.
- UI to edit remembered device = delete device & toggle auto connect
