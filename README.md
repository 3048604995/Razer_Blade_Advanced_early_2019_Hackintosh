# Razer_Blade_Advanced_early_2019_Hackintosh
Razer Blade Advanced early 2019 macOS Big Sur Hackintosh
Razer Blade Advanced early 2019

Spec	macOS 10.14 compatibility
Chipset	Mobile Intel HM370	No issues
CPU	Intel Core i7-8750H processor, 6 Cores / 12 Threads, 2.2GHz / 4.1GHz, 9MB Cache	No issues
Memory	16GB dual-channel DDR4-2667MHz, up to 64GB	No issues
GPU	Intel UHD 630	No issues
dGPU	Nvidia 2070 Max-Q (8GB GDDR6 VRAM)	Nvidia Drivers absent for Mojave. ACPI should be patched to disable dGPU
Storage	Samsung PM981 256GB NVMe M.2	Incompatible firmware. You can install macOS on compatible
Screen	15.6" Full HD 144Hz, 1920 x 1080 IPS	No issues
Webcam	Windows Hello built-in IR HD webcam (1MP / 720P)	No issues. Windows Hello is not supported in macOS
WiFi	Intel Wireless-AC 9560NGW	Drivers absent for macOS. Should replaced
Input & Output	USB 3.1 Gen 1 (USB-A) x3	No issues
Thunderbolt 3 (USB-C)	No issues
HDMI 2.0B	HDMI connected directly to Nvidia GPU and will not work in macOS
Mini DisplayPort 1.4	Mini DisplayPort connected directly to Nvidia GPU and will not work in macOS
Soundboard	Realtek ALC298	No issues. ACPI patch should be added to solve sleep issue
Battery	80Wh	About 3-5h after proper Power Management configuration. ACPI should be patched to enable battery stats
Keyboard	Per-key RGB powered by Razer Chroma N-Key rollover backlit	No issues. Original Razer Chroma software absent for macOS. Many thanks to BlvckBytes for MenuBar app to control Razer Blade keyboard and logo RGB lighting
Touchpad	Precision Glass	No issues. ACPI should be patched to enable trackpad
Dimensions	17.8mm x 235mm x 355mm	
Weight	2.21 kg	ACPI patches will not help with this. /sarcasm
Power	230W power adapter
