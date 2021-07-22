# Dell G3 3500 Opencore Hackintosh
Dell G3 3500 Opencore Hackintosh


Note: There's no SMBIOS info. You need to generate your own serial and change it from config.plist. Set GenSMBIOS for MacBookPro16,4


Opencore 0.6.6

## Specs: 

- CPU: Intel Core i5-10300H 2.5 GHz Quad Core
- RAM: 8 GB DDR4 2933 MHz (2 x 4GB)
- iGPU: Intel UHD 630
- dGPU: Nvidia GTX 1650Ti 8 GB
- SSD: 512 GB NVMe
- Display: 15.6" 1920 x 1080 60 Hz
- Sound: Realtek ALC 295
- Ethernet: RTL8111
- WiFi: Intel AC9462 2nd Gen
- Bluetooth: Intel (combined with AC9462)
- 2x USB 2.0
- 1x USB 3.2 Gen 1 with PowerShare
- 1x USB 3.2 Gen 2 (Type-C) port with DisplayPort Alt-Mode 

## What's working:

- CPU with proper power management
- iGPU
- Ethernet
- Wifi
- External monitor via DisplayPort Alt-Mode on Type-C port (when dGPU is not disable)**
- Bluetooth
- Brightness keys
- Webcam
- Sound
- Touchpad with gestures
- SD Card Reader
- iMessage, Facetime etc.

## What isn't working:

- HDMI port (its hardwired to dGPU)
- Headphone jack (sound is scrambled and it doesn't detect microphone(but you can use USB ports for audio input and output))
- Internal microphone
- External monitor via DisplayPort Alt-Mode on Type-C port (when dGPU is disable) **
- Brightness keys (when dGPU is not disable) **

## Not tested:

- idk
