# Ender-5 S1 - Klipper Install Guide
This is a guide for installing and using Klipper on the Ender 5 S1 without a Sonic Pad (and other Ender 5 S1 related resources...)

## Building Klipper
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
