# iOS-nRF-Connect
This repository is used to submit any iOS-nRF Connect issues and feedback. 

## Project history
This project started at end of 2015, the aim is to make a comprehensive Bluetooth tool for both firmware developers and App developers.

## Current Version
The current version "nRF Connect" formerly known as "nRF Master Control Panel", includes the following features:
- Supports DFU
- Scans for BLE devices
- Shows advertisement data
- Shows RSSI in chart
- Logs Bluetooth related events and method calls
- Connects to any connectable the Bluetooth Smart device
- Discoveries services and characteristics
- Allows to read and write characteristics
- Allows to enable and disable notifications and indications
- Supports the Nordic UART Service
- Parses Apple's and Google's standards of beacons
- Advertise as a peripheral 
- Nordic Thingy 

### RSSI chart
The RSSI chart feature is available from the version 1.5. The linear curve describes relative distance between a phone/tablet and peripheral. Theoretically, When received RSSI number is bigger, it is closer to the periperal. The calculation is limited to an unchanged transmit power and ignorance of other parts might cause signal fading.

### Log
The log feature is available from the version 1.5. nRF Connect provides 6 levels of log.
- Debug - system level action
- Verbose - user interaction  
- Info - client action
- Application - data usage
- Warning - system validation
- Error - system error

### Beacon
nRF Connect support Apple's and Google's standard beacon.
You find Apple's specification here: https://developer.apple.com/ibeacon/
For Google: https://github.com/google/eddystone/blob/master/protocol-specification.md
(Eddystone-UID, Eddystone-URL, Eddystone-TLM are supported)

## Roadmap 
- GATT Profiles support
- Imporving UI
- GATT Server configuration

## Related Projects
- https://github.com/NordicSemiconductor/IOS-DFU-Library
- https://github.com/NordicSemiconductor/IOS-Pods-DFU-Library
- https://github.com/NordicSemiconductor/Android-nRF-Connect
- https://github.com/NordicSemiconductor/Android-DFU-Library
- https://www.nordicsemi.com/Products/Bluetooth-low-energy/nRF-Connect-for-desktop
