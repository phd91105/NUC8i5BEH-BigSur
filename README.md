# NUC8I5BEH Hackintosh

### Specs
|SPECS| |
|---|---|
|CPU|Intel Core i5-8259U|
|System Memory|2x16GB (Sk Hynix)|
|Display|Intel Iris Plus Graphics 655|
|Audio Adapter|Realtek ALC235|
|Storage|Samsung 970 EVO Plus|
|Network|Intel Wireless-AC 9560|

### Installation
+ Update to the latest BIOS -> load BIOS defaults -> click advanced and change;
```
Devices -> USB -> Port Device Charging Mode: off
Devices -> USB -> USB Legacy -> Disabled
Security -> Thunderbolt Security Level: Legacy Mode
Power -> Wake on LAN from S4/S5: Stay Off
Boot -> Boot Configuration -> Network Boot: Disable
Boot -> Secure Boot -> Disable
```
