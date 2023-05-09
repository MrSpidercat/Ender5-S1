# Ender-5 S1 Resources
This repository contains resources fpr the Ender 5 S1 from firmware configuration to recommended slicer settings, feel free to create a PR if you feel that anything needs to be added.

## Links

#### Recommended Slicer
- [PrusaSlicer 2.6.0 Alpha](https://github.com/prusa3d/PrusaSlicer/releases)
> **Note**:
>  This is the only slicer that comes stock with a profile for the 5S1 besides Creality Slicer.

#### Firmware
- [Stock/Marlin Source Code](https://github.com/CrealityOfficial/Ender-5S1)

  - [Marlin Configuration](https://github.com/MarlinFirmware/Configurations/tree/import-2.1.x/config/examples/Creality/Ender-5%20S1) 

- [Sonic Pad Source Code](https://github.com/CrealityOfficial/Creality_Sonic_Pad)

  - [Klipper Configuration](https://github.com/MrSpidercat/Ender5-S1/tree/main/Klipper)




## Klipper Build Guide
> This guide goes over how to build Klipper from source for this printer.
1. Obtain a configuration file for the 5S1, there is a few options provided in the Klipper folder located in this repository.
2. Clone the Klipper repo `git clone https://github.com/Klipper3d/klipper`
3. Run `make menuconfig` in the Klipper directory then set all the options accordingly
```
- Micro-controller Architechture: SMTMicroelectronics STM32
  - Processor Model: STM32F401
- Bootloader offset: 64KiB bootloader
- Communication interface: USB (on PA11/PA12)
```
4. Run `make` 

(to be completed....)


## Marlin Build Guide
> This guide goes over how to build Marlin from source for this printer.

(to be completed....)

