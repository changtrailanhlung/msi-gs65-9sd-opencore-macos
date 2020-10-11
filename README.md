# msi-gs65-9sd-opencore-macos
This is an OpenCore EFI that allows you to install and boot macOS X Catalina on your Dell XPS 15 9500 (2020).

**OpenCore Version:** 0.6.1

**macOS Version:** Catalina 10.15.7

---

##Functional Status

|Function / Hardware|Status|
|-------------------|------|
|iGPU UHD630 Acceleration|Working|
|dGPU NVIDIA GTX1660Ti Acceleration|Not Working|
|CPU Power Management|Working - idles at 800MHz, boosts to max Turbo frequency|
|Laptop Keyboard|Working - missing control LED (SSE3)|
|Laptop Trackpad|Working|
|Laptop Headphones Jack|Working|
|Built-in Speakers|Working - missing NAHIMIC|
|Built-in Mic|Working|
|Hotkeys for audio, brightness, webcam, touchpad|Working|
|USB 3.x|Working|
|Screen brightness|Working, hotkeys fn+PGUP/fn+PGDN to increase/decrease brightness|
|Built-in Wifi|Working|
|Built-in Bluetooth|Working|
|USB type C - thunderbolt 3|Working|
|Killer E2500 Ethernet|Working|
|Built-in webcam|Working|

---

##Pre-Installation

MSI Bios Menu Setup
Advanced

Sata mode = AHCI (Only necessary if you're not using an external SSD to install macOS. Warning: if switched from RAID to AHCI, your Windows install and all data will be lost)
VT-d = Disabled
Boot

Fastboot = disabled
Boot mode = UEFI with CSM
Security

Secure boot = disabled