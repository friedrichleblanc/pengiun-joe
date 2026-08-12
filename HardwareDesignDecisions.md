# Hardware Design Decisions

## Main Processor Board

### Main MCU Esp32-wrooom-32u

This board was selected due to having option use external antenna that will help to capture signals outside of the shell.

### Stackup

4-layer board that has 2 internal GND pours. 

SIGNAL/POWER
GND
GND
SIGNAL/POWER


### Power

USB-C was used for both power and for programming of the MCU. It also provides stable 5V to the so-called Amplifier.

### LDO 

XC6220B331MR was used to reduce voltage from 5V to 3.3V@1A. Parts other than Amplifier connected to this LDO.

### USB-UART

CH340C was used as programmer enhanced with auto-upload circuit

### ESD protection

USBLC6-2SC6 was used in order to prevent Electro-shock off data traces and 5V power trace.


### Amplifier
MAX98357A was selected due to its low cost.

### Hirose FH12 

You maybe familiar with similar connector used in PS4 controllers. It was used to connect board to microphone board.

## Microphone board

### Microphone

ICS-43434 is used due to its excellent sound capturing abilities:)

### Hirose FH12 

You maybe familiar with similar connector used in PS4 controllers. It was used to connect microphone to the main board.
