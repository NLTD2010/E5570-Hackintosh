# E5570-Hackintosh
Dell Latitude E5570 Hackintosh Project
![Picture](https://github.com/quynkk1/E5570-Hackintosh/blob/main/wallpaper/screenshot.png)

## Specification:
- CPU + GPU: Core i3-6100U with HD 620
- Memory: 12GB
- LAN: I219
- Wireless/Bluetooth: Intel AC 8260
- 3 Ports of USB, VGA, HDMI, SDCard (Realtek)
- Audio Codec: ALC293

## Bootloader:
- Supported 2 types of bootloader: OpenCore (0.7.6) + Clover (R5142)

## What's working?
- Support macOS Mojave / Catalina / Big Sur / Monterey
- QE/CI: 1536MB VRAM
- Brightness control
- Sleep when lid closed
- Charging
- CPU Power Optimized
- USB Port (3 Ports, 3.0)
- LAN Port
- Wireless and Bluetooth
- Keyboard and trackpad (ALPS v8)
- Audio, Microphone (with headphones jack)
- HDMI (with audio output), VGA Port

## What's not working or BUGs?
- Trackpad: Show not detected in System Preferences but you can still move your cursor and gesture with 2 fingers.
- HDMI: Sleep and wake your laptop before use it.
- Realtek SD-Card: It will stop working after sleep, you need to restart your hacks to make it works again.

## Note:
- You need to add your wireless and bluetooth drivers/kexts manually depend on your hardware
- Remap USB after installed macOS
- If you use macOS Big Sur 11.0 - 11.2.3, you need to enable XHCIPortLimit quirks in config.
- For CPU Optimization, use this guide: [CPUFriend](https://dortania.github.io/OpenCore-Post-Install/universal/pm.html#using-cpu-friend).

## Download:
- Wallpaper: https://github.com/quynkk1/E5570-Hackintosh/blob/main/wallpaper/Wallpaper.jpg
- EFI: Release section.

## Thanks:
- [Apple](https://www.apple.com/macos/monterey/) for macOS.
- [SergeySlice](https://github.com/CloverHackyColor/CloverBootloader) for Clover Bootloader.
- [Acidanthera](https://github.com/acidanthera) for OpenCore, Lilu, WEG, ... and other devs for many kext I used.
