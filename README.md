# Dell Precision 3620 Tower Hackintosh

## Configuration

| Specifications      | Detail                       |
| ------------------- | ---------------------------- |
| CPU                 | Intel Core i5-6600 |
| Integrated Graphics | Intel HD Graphics 530 |
| Sound Card          | Realtek ALC236 (layout-id:3) |
| Wireless Card       | Intel AX200              |

## MacOS Versions Tested:

- macOS Sonoma

## Changelog

### 05/15/2024

#### Preliminary release 

## What is Working?

- [x] Sleep/Wake
- [x] Intel Graphics
- [x] Onboard Speakers
- [x] HDMI: Video and Audio
- [x] Display Port: Video and Audio
- [x] USB 3.0
- [x] Built-in mic
- [x] Line-in mic
- [x] Fn keys: play/pause, prt scr(F13), sound mute/-/+, sleep

## Not working:

## BIOS settings

- [ ] Fast Boot
- Secure Boot Configurations - Configure Legacy Support and Secure Boot = Legacy Support Disable and Secure Boot Disable
- [ ] VTx in System Options
- Wake On LAN = Disabled
- Wake On WLAN = Disabled
- Video Memory size = 64 MB
- Wake on USB = optional

## IMPORTANT

Make sure to add SMBIOS of iMac TBD and serial number in config.plist.
