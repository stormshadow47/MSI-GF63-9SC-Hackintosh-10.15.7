# MSI-GF63-9SC-Hackintosh-10.15.7[Opencore 0.6.7]
MacOS Catalina 10.15.7 runs perfectly with full hardware acceleration and no issues so far. I'll update this repository after uprading to Big Sur later on.

Laptop Specs:
- CPU: Intel Core i5 9300H
- GPU: Nvidia GTX 1650 max-q
- RAM: 16GB DDR4-2666 MHz
- WI-FI: Intel Wireless AC9560
- LAN: Realtek Gbe

What's working:
- Intel UHD 630 iGPU with 1536 MB.
- WiFi(AC9560) both 2.4GHz and 5GHz bands.
- Bluetooth and audio through bluetooth.
- Ethernet( Have to set MAC address manually in system preferences).
- USB Ports.
- Sleep/wake functionality.
- Keyboard and Trackpad.
- Onboard speakers.
- 3.5mm Audio and Mic jacks.
- iMessage and FaceTime.
- Onboard Webcam.

What's broken:
- GTX 1650 max-q eGPU (disabled,obviously).


Note:
- I'd recommend creating your own kext and ACPI files as these files aren't guaranteed to work even on identical systems. I've uploaded these files as a guide to what all files are needed for this specific machine.
- Following Dortania's OC guide is highly recommended. It is the go to guide for hackintoshing and read it as if you're a pastor reading the bible.
- To fix iMessage and FaceTime, I had to resort to an unholy method of contacting apple support. Got my account blacklisted after attemting to sign in with an error ridden platfrom infromation in my config.plist. 
- I've since fixed my plist file and after contacting apple support, iMessage works just fine.
- Haven't tested the HDMI output yet. I'll update if it works or not after testing.

