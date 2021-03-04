# EFI for hackintosh-x1c-5th
Hackintosh DSDT/SSDT &amp; CLOVER backup for Thinkpad X1 Carbon 5th Gen (2017)  

This is basically a fork of [@tylernguyen](https://github.com/tylernguyen)'s hackintosh repo ([here](https://github.com/tylernguyen/x1c6-hackintosh)) on X1 Carbon 6th Gen. Drivers and configurations are modified according to my own device's specifications and my own needs. Feel free to try out this EFI but at your own risk.  

I'm using Intel WiFi and network is made possible by [@OpenIntelWireless](https://github.com/OpenIntelWireless). Airdrop and handoff stuff are not working as expected, for more info visit OpenIntelWireless documentation.

## Current running OS  
macOS Catalina 10.15.6

## Specifications
Model: ThinkPad X1 Carbon 5th Gen (2017)
| Processor Number                                                                                                                   | # of Cores | # of Threads | Base Frequency | Max Turbo Frequency | Cache | Memory Types | Graphics      |
| :--------------------------------------------------------------------------------------------------------------------------------- | :--------- | :----------- | :------------- | :------------------ | :---- | :----------- | :------------ |
| i5-7300U | 2          | 4            | 2.6 GHz        | 3.5 GHz             | 3 MB  | LPDDR3-1867  | Intel HD 620 |

**Peripherals:**

```
Two USB 3.1 Gen 1 (Right USB Always On)
Two USB 3.1 Type-C Gen 2 / Thunderbolt 3 (Max 5120x2880 @60Hz)
HDMI 1.4b (Max 4096x2160 @30Hz)
Ethernet via ThinkPad Ethernet Extension Cable Gen 2: I219-LM Ethernet (vPro)
No WWAN
TrackPoint: PS/2
TrackPad: PS/2
```

**Display:**  
`14.0" (355mm) HDR WQHD (2560x1440)`  
**Audio:**  
`ALC285 Audio Codec`  
**Thunderbolt:**  
`Intel JHL6540 (Alpine Ridge 4C) Thunderbolt 3 Bridge`  
**WiFi Card:**  
`Intel AX200`
