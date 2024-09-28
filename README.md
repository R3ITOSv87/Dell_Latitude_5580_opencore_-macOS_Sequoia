# Dell Latitude 5580 Hackintosh Sequoia OpenCore 1.0.1
![macOS](https://img.shields.io/badge/macOS-Sequoia-green.svg)
![version](https://img.shields.io/badge/15.0-red)
![OpenCore](https://img.shields.io/badge/OpenCore-1.0.1-green)
![LICENSE](https://img.shields.io/badge/license-MIT-green.svg)

Fork from https://github.com/TechMangaOfficial/Dell_Latitude_5480_Hackintosh | Thanks to @TechMangaOfficial
#
This repo contains the files necessary to install Sequoia on Dell latitude 5580 and 5480. 

# Specification 
- <b>Model</b>: Dell Latitude 5580 (5480 should also Work) 
- <b>CPU</b>: Intel(R) Core(TM) i5-6300U CPU @ 2.50GHz
- <b>GPU</b>: Intel HD Graphics 520
- <b>RAM</b>: 16 GB 2133MHz DDR4
- <b>Storage</b>: 512GB NVME SSD
- <b>Screen</b>: 15,6" (1920x1080)
- <b>Wi-Fi</b>: Intel Dual Band Wireless-AC8625
- <b>Ethernet</b>: Intel Ethernet I219-LM
- <b>Camera</b>: 720p
- <b>Touchpad</b>: Alpsalpine I2C
- <b>Battery</b>: 3-cell with inside battery 

# What's Working?
- [x] Wi-Fi (Heliport needed!)
- [x] Intel HD 520 Graphics (with graphics acceleration spoofed as Intel HD 620)
- [x] HDMI port (With HDMI Audio no purple tint)
- [x] Internel Speaker
- [x] Headphone Jack
- [x] Internal camera 
- [x] Trackpad (multigestures work use tap to click option)
- [x] CPU Power Management 
- [x] All USB ports
- [x] Keyboard (all fn Keys Brightness key works)
- [x] Intel Ethernet port
- [x] iMessage, FaceTime, App Store, iTunes Store (with valid smbios)
- [x] DRM support 
- [x] Sleep / Wake (lid sleep and lid wake) 

# What's not working ⚠️
- [x] Handoff, Universal control, Airdrop (Unless you have Broadcom wifi Card)
- [x] SD Card Reader (Damaged so can't test)
- [x] Bluetooth
- [x] WPA-3 WiFi-Networks for some reason 

# Solutions 
- [x] If your CPU usage is high try
```
sudo launchctl disable gui/501/com.apple.transparencyd
```
# Refrences
- [Dortania Opencore Guide](https://dortania.github.io/OpenCore-Install-Guide/)


