# HP-800-G1-SFF-HD4600-OpenCore
OpenCore for HP 800-G1 SFF with HD4600

#OC information

    OC Version: 0.7.4
    Tested OS Version: 11.6 
    Tested resolution: 1920*1080

#Working

    WIFI(Intel or Broadcom )
    Sound
    USB Port

#Before installation
Edit config.plist

At first, please complete the 'PlatformInfo' by yourself. https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html#platforminfo

    PlatformInfo>Generic>MLB
    PlatformInfo>Generic>ROM
    PlatformInfo>Generic>SystemSerialNumber
    PlatformInfo>Generic>SystemUUID

BIOS Settings
Disable

    Fast Boot -> Disabled
    Secure Boot -> Disabled
    Security -> VTd -> Disabled

Set

    Storage -> Storage Options -> SATA Emulation > AHCI

Kext information
Name 	Version
Lilu 	1.5.6
VirtualSMC 	1.2.7
WhateverGreen 	1.5.4
AppleALC 	1.6.5
AirportItlwm 	2.0.0
AirportBrcmFixup 	2.1.3
BrcmPatchRAM 	2.6.0
IntelMausi 	1.0.7
USBInjectAll 	0.7.6
