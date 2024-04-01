![Header](https://github.com/NordicSemiconductor/IOS-nRF-Connect/blob/master/header.png)
# nRF Connect for iOS
This repository is used to submit any nRF Connect for iOS issues and feedback. 

## Project history
This project started at end of 2015, with the aim is to make a comprehensive Bluetooth tool for both firmware developers and App developers. This development train lead to the release of version 1.8.8 in September 2018, at which point development was rebooted from scratch, culminating in the release of the all-new nRF Connect 2.0 on August 19th, 2019. We intend to make this 2.0 version the basis of all future development.

## Features
The current version nRF Connect (formerly known as "nRF Master Control Panel"), includes the following features:
- BLE Device Scanning, and comprehensive filtering solutions
- RSSI Graph View of scanned devices
- Connects to any connectable the Bluetooth Smart device
- Service, Characteristic and Descriptor Discovery
- Read and Write Characteristic(s) and Descriptors
- Enable and Disable Notifications and Indications
- Logs for Bluetooth related events and method calls, as well as DFU (new as of version 2.3)
- Device Firmware Update, for both 'Nordic' DFU and McuMgr DFU
- Parses Apple's and Google's standards of beacons
- Advertising as a BLE Peripheral
- Importing Files via Drag & Drop
- Full iPad OS Support, including resizable window, pop-over, and Mouse Support.
- [Online Service & Characteristic Repository](https://github.com/NordicSemiconductor/bluetooth-numbers-database), updated on app startup.

### Supported Devices
nRF Connect 2.x runs on all iPhone(s) and iPad(s) running iOS 9 and newer, up to iOS 13. We intend to keep making the newest version of nRF Connect available on the greatest amount of devices as possible. However, please keep in mind that not all features will be present, and that we can't optimise the UI for each and every single use case.

## Roadmap
Please keep in mind that the following information is representative of the team's intentions, and in no way should be taken as final. Priorities change, as well as unexpected issues & bugs we might decide are more important and need our immediate attention.

Version 2.4:
- GATT Server Support

After version 2.4:
- iOS 14 Support
- Improved in-app feedback and crash reporting

### Will there be a Mac/Catalyst port of nRF Connect for iOS?
Since macOS Catalina (10.15), Apple allows [iOS apps to be compiled and run in near-native form on the Mac](https://developer.apple.com/mac-catalyst/). There is already a [Desktop version of nRF Connect](https://www.nordicsemi.com/Software-and-tools/Development-Tools/nRF-Connect-for-desktop) under full development and support from a dedicated team, so there are no plans as of yet to publish nRF Connect for iOS on the Mac App Store.

That being said, some users have requested us to ship nRF Connect for iOS as a Mac app. If you too are interested, please let us know; the more demand we can see, the easier it is for us to devote the resources needed to make it happen.

## Swift Development
Early on after the release of version 2.0, we published a few blog posts regarding its [full feature set](https://devzone.nordicsemi.com/nordic/nordic-blog/b/blog/posts/announcing-nrf-connect-2-0-for-ios), the amount of [work and detail we pour into a bug-fix release](https://devzone.nordicsemi.com/nordic/nordic-blog/b/blog/posts/nrf_2d00_connect_2d00_ios_2d00_2_2d00_0_2d00_3_2d00_what_2d00_is_2d00_a_2d00_bugfix_2d00_release), and [our transition to Dark Mode in 2.1](https://devzone.nordicsemi.com/nordic/nordic-blog/b/blog/posts/nrf_2d00_connect_2d00_ios_2d00_dark_2d00_mode).

Since then, we've transitioned towards blogging less-often, but attempting to offer a unique perspective focused more on using all the development tools at our disposal to extract more performance out of iOS hardware:
- [SIMD Optimizations in Swift](https://devzone.nordicsemi.com/nordic/nordic-blog/b/blog/posts/nrf_2d00_connect_2d00_simd_2d00_optimizations_2d00_in_2d00_swift)
- [From a BitField Collection in Swift downto x86 Assembly](https://devzone.nordicsemi.com/nordic/nordic-blog/b/blog/posts/on-nrf-connect-for-ios-and-its-unnecessary-bitfield-collection-in-swift)

### Related Projects
- [iOS DFU/McuMgr Library](https://github.com/NordicSemiconductor/IOS-Pods-DFU-Library)
- [nRF Connect for Android](https://github.com/NordicSemiconductor/Android-nRF-Connect)
- [Android DFU/McuMgr Library](https://github.com/NordicSemiconductor/Android-DFU-Library)
- [nRF Connect for Desktop GitHub Page](https://github.com/NordicSemiconductor/pc-nrfconnect-launcher)
