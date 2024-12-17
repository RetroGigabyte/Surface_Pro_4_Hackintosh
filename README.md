# Surface Pro 4 i7 Hackintosh
This provides the ability to boot the Surface Pro 4 i7 to macOS as a hackintosh.  

EFI supports macOS version 10.15 through 15.2.

Star or watch this github repository to be notified of updates coming soon. 

If you see anything that could be added or changed don't hesitate to sumbit a request.


## *** NOTICE ***
- ### Touch is Technically supported in the posted EFI files however it requires [@Xiashangning's IPTSDaemon](https://github.com/Xiashangning/IPTSDaemon) in order to work. Please see the "Chapter 3" link below for instruction.
- ### If you have issues with random reboots at the user creation screen after install of macOS Big Sur and newer it is because you have chosen an incorrect config.plist file. Please ensure that you are using the correct one for your system.

 

## Supported Software:

- [X] macOS 10.15 Catalina (End of Life)
- [X] macOS 11 Big Sur (End of Life)
- [X] macOS 12 Monterey (Unsuported by apple for updates)
- [X] macOS 13 Ventura
- [X] macOS 14 Sonoma
- [x] macOS 15 Sequoia
- [ ] macOS 16 (Expected to end support for Intel)


## Instruction Guides

### [Chapter 1) Quick Start Install](https://github.com/balopez83/Surface-Pro-4-and-Surface-Book-Hackintosh/blob/main/1-QuickStart.md)
### [Chapter 2) BootCamp Install](https://github.com/balopez83/Surface-Pro-4-and-Surface-Book-Hackintosh/blob/main/2-BootCamp.md)
### [Chapter 3) Quirks & Fixes - Includes how to set up the Touch Screen](https://github.com/balopez83/Surface-Pro-4-and-Surface-Book-Hackintosh/blob/main/3-quirks%26fixes.md)
### [Chapter 4) Additional Drivers](https://github.com/balopez83/Surface-Pro-4-and-Surface-Book-Hackintosh/blob/main/4-drivers.md)
### [Chapter 5) Booting Other OS's with OpenCore](https://github.com/balopez83/Surface-Pro-4-and-Surface-Book-Hackintosh/blob/main/5-OtherOS%26OC.md)
### [Chapter 6) Windows 11 Upgrade and/or Clean Install]
### [Chapter 7) Enable Secure Boot with OpenCore/macOS](https://github.com/balopez83/Surface-Pro-4-and-Surface-Book-Hackintosh/blob/main/7-SecureBootOn.md)


## What works 

- macOS Installer
- macOS Updates
- Fan
- USB
- Battery
- Trackpad
- TouchScreen (Requires IPTSDaemon, "Chapter 3")
- Keyboard
- Audio
- Recovery
- Brightness Keys
- Power Management
- Sleep / Wake
- Power Button
- Volume Buttons
- UEFI Secure Boot ON
- SD card
- FileVault
- Dual Boot with Windows
- Dual Boot with Linux
- Dual Boot with chromeOS
- Surface Keyboard Hot Plug
- Surface Dock
- Deep Sleep (macOS Hibernation 'Hibernatemode=25')
- mDP 





## What doesn't work

- Wi-Fi (unsupported Chipset)
- Bluetooth (unsupported Chipset)
- Accelerometer (unsupported device)
- Cameras (unsupported device)
- Hardware based DRM (Apple Issue)





## Credits
Special thanks to [@Xiashangning](https://github.com/Xiashangning) for the excellent work done on his BigSurface kext as well as [@billabongbruno](https://github.com/billabongbruno) for other Surface specific enhancements<br>
