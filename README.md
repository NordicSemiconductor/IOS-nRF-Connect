# iOS-nRF-Connect
This repository is used to submit any iOS-nRF Connect issues and feedback. 

## Project history
This project started at end of 2015, the aim is to make a comprehensive Bluetooth tool for both firmware developers and App developers.

## Current Version
The current version "nRF Connect" formerly known as "nRF Master Control Panel", includes the following features:
- Scans for Bluetooth low energy (LE) (or called Bluetooth Smart)devices
- Shows advertisement data
- Shows RSSI in chart
- Logs Bluetooth related events and method calls
- Connects to any connectable the Bluetooth Smart device
- Discoveries services and characteristics
- Allows to read and write characteristics
- Allows to enable and disable notifications and indications
- Supports the Nordic UART Service
- Parses Apple's and Google's standards of beacons 

## RSSI chart
The RSSI chart feature is available from the version 1.5. The flowing chart shows relative distance changing between your phone/tablet and peripheral. Theoretically, When received RSSI number is bigger, it is closer to the periperal. The calculation is limited to an unchanged transmit power and ignorance of other parts might cause signal fading.

## Roadmap 
- Device Firmware Update (DFU) support
- GATT Profiles support
- Imporving UI
- GATT Server configuration

## Related Projects
- https://github.com/NordicSemiconductor/IOS-DFU-Library
- https://github.com/NordicSemiconductor/IOS-Pods-DFU-Library
- https://github.com/NordicSemiconductor/Android-nRF-Connect
- https://github.com/NordicSemiconductor/Android-DFU-Library
- https://devzone.nordicsemi.com/blogs/922/nrf-connect-v10-release-candidate/
