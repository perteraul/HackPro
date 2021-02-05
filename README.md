# HackPro


This repository aims to walkthrough the process of building my Hackintosh - including the EFI folder and sharing the components I used. 


Bootloader: **OpenCore 0.6.6**  
macOS: **Big Sur 11.2**  
Status: **Stable**

----

### Hardware:

· CPU: Intel i9-10900K  
· GPU: Sapphire Radeon RXX 5700XT Nitro+ SE  
· Motherboard: Gigabyte Z490 Aorus Ultra  
· Memory: Corsair Vengeance RGB Pro 64GB  
· Storage: 2x ADATA SX8200 PRo 512GB M.2 && Seagate BarraCuda 2TB SATA-III  
· Cooling: Noctua NH-D15 Chromax Black  
· Power: Seasonic Focus GX 850W 

*Extra stuff to make it better:*  
· Gigabyte Titan-Ridge rev. 2 (needed for the LG 5K UltraFine diplay)  
· Fenvi T919 (Bluetooth & WiFi)


### Peripherals:

· Display: LG UltraFine 5K  
· Mouse: Logitech MX Master 3  
· Keyboard: Logitech MX Keys  
· Microphone: Blue Yeti  
· Webcam: iPhone 6S + Reincubate Camo  
· Speakers: Logitech G560  

--- 

### Here's what works:
- [x] Bluetooth && WiFi, due to using the Fenvi T919 card and also disabling the onboard Bluetooth.
- [x] Audio
- [x] iMesssage, AirDrop and SideCar
- [x] DRM (Netflix)
- [x] Sleep && Wake
- [x] Shutdown && Restart
- [x] USB  
- [x] 1Gbit Ethernet 

### Untested so far:
· 2.5Gbit Ethernet  
· AppleTV

---

### Disclaimer:
If you'll use this configuration, I highly recommend that you do follow Dortania's guide and make your own setup. Yes, I know it's pretty long but give it a read and you'll end up with an almost-perfect Hackintosh. 

If you still want to use this config, make sure to replace the `*GENERATE*` entries in the `config.plist`. You can generate your own serial number with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS). 


