# ender3marlin
Precompiled Binaries for Ender3 Vanilla Marlin

Due to the difficulty some people are having with getting the latest Marlin (1.1.x-Bugfix) code to compile with Mesh Leveling while still fitting in the constraints of the sanguino1284p's capacity, I have decided to keep an as up to date collection of binaries for people to use.  

These are provided without warranty, expressed or implied, but have been tested to be functional on my Ender 3 Sanguino1284p.

This repository should make it easier for people who wish to upgrade, but do not want to get involved with Arduino code hacking.

Since most people with access to Arduino hardware, often used to program the Ender 3, would not have issue with making their own binaries, the following web site is an excellent resource for those of us with Raspberry Pi SBCs.  

https://www.fission3d.com/guides/flash-bootloader-and-install-firmware-with-raspberry-pi

This site will tell you how to hook a Pi up via GPIO to the ICSP pins of the Ender 3's mainboard, gaining you access to flash a bootloader, which will then allow you to flash the precompiled binary of your choice.


--------------

optiboot_atmega1284p.hex - ATMega1284p Bootloader, required only once to open Sanguino1284p board for firmware flashing.

Marlin-1.1.9.hex	- Vanilla Marlin, 1.1.9. Final version as of code freeze. Configured for Ender 3.

Marlin-1.1.x-bugfix.hex	- Vanilla Marlin, 1.1.x-bugfix. No modification of features. Configured for Ender 3.

Marlin_1.1.x-bugfix_Mesh_Leveling.hex - Vanilla Marlin, 1.1.x. Arc Support and Boot Screen Logo disabled to allow room for Mesh Leveling feature. Configured for Ender 3.

--------------
