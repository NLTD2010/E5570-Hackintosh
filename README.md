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

## What's working?
- Using Clover Bootloader R5142 with lastest driver and kexts
- Support macOS Mojave / Catalina / Big Sur / Monterey
- QE/CI: 1536MB VRAM
- Brightness control
- Sleep when lid closed
- Charging
- USB Port (3 Ports, 3.0)
- LAN Port
- Wireless and Bluetooth
- Keyboard and trackpad (ALPS v8)
- Audio, Microphone (with headphones jack)
- HDMI (with audio output), VGA Port

## What's not working or BUGs?
- Trackpad: Show not detected in System Preferences but you can still move your cursor. I'm rewriting VoodooPS2 (from Acidanthera, SkyrilHD) to make it works perfectly.
- HDMI: Sleep and wake your laptop before use it.
- Realtek SD-Card: It will stop working after sleep, you need to restart your hacks to make it works again.

## Note:
- You need to add your wireless and bluetooth drivers/kexts manually depend on your hardware
- Remap USB after installed macOS
- If you use macOS Big Sur 11.0 - 11.2.3, you need to enable XHCIPortLimit quirks in config.

## Download:
- Wallpaper: https://github.com/quynkk1/E5570-Hackintosh/blob/main/wallpaper/Wallpaper.jpg
- EFI: Release section.

## Thanks:
- Apple for macOS.
- Acidanthera and other devs for many kext I used.
- SergeySlice for Clover Bootloader.
