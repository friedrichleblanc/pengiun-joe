# Pengiun-joe
## Esp32 based talk-back bot features external custom microphone module.
## Description 
### Motivation
It is like to have companion with you while coding, wathing or ext. And what if that companion is an Pengiun joe?

## Hardware

Penguin Joe uses a two-board modular architecture:

### Schematics 
[Microphone](docs/ICS-43434 Microphone.pdf)
### Main Board

The main board contains the Esp32 processor, XC6220B331MR LDO ,MAX98357A amplifier.

Board uses 5V@2A for amplifier and 3.3v@1A for other components.

(<img src="Doc/3dMainFront.jpg" width="300">) (<img src="Doc/3dMainBack.jpg" width="300">) 

### Microphone Board

Separated Microphone MODULE was designed for the placement in shell.

(<img src="Doc/Pengiun_Mic(ICS-43434).png" width="300">) (<img src="Doc/Pengiun_Mic(Back)(ICS-43434).png" width="300">) 
