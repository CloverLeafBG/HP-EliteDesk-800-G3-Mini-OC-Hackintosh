# HP-EliteDesk-800-G3-Mini-OC-Hackintosh


OpenCore based EFI for HP EliteDesk 800 G3 Mini.

![hp](https://user-images.githubusercontent.com/93620854/212490075-5390ef5f-fd90-4c76-ad38-4487d1f2bc08.png)





## Tested macOS Version


- macOS Sonoma 14.5


## System Configuration

- CPU:  Intel Core i7-7700
- iGPU: Intel HD Graphics 630
- RAM:  16GB DDR4 2400Mhz
- SSD:  WD SN730 500GB
- WiFi & Bluetooth: Intel 8265NGW
- Sound Card: Conexant CX20632
- LAN: Intel I219-LM

### BIOS Version

2.49 Rev.A


### Bootloader

OpenCore 1.0.0

### SMBIOS

Macmini8,1



## What's working

 - [x] Power Management
 
 - [x] iGPU Acceleration - hot pluggable display ports and DP->DVI adapters

 - [x] Audio (internal speaker, headphone jack and audio over DP)
 
 - [x] WiFi
 
 - [x] Bluetooth

 - [x] Ethernet

 - [x] USB 3.0 and USB-C
 


## What's not working

- [ ] DRM
      
- [ ] Sleep/Wake


## Additional Notes

Don't forget to generate your own SMBIOS with https://github.com/corpnewt/GenSMBIOS. 

- ENJOY!
