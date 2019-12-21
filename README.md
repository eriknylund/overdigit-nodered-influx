# Parts

- FT232RL RS485 to USB serial adapter
https://www.aliexpress.com/item/32956970166.html?spm=a2g0s.9042311.0.0.523e4c4dtqKiFk

- Overdigit EX08AI
https://web-plc.com/product/modbus-analog-input-module-ex08ai/

- Raspberry Pi 2 or newer
https://www.raspberrypi.org/

# Drivers, Manuals and Tools

CH-340 VCP  http://www.ftdichip.com/Drivers/VCP.htm 

# Wiring

EX08AI - (A) -> RS485 + 
EX08AI + (B) -> RS485 -

# Configuration

Default: Baudrate: 9600 baud, Parity: even

## Configure port using tool

The devide requires that both the physical DIP switches are correctly placed, and then also that the register for the corresponding port is set. This is easiest done through the Modbus-Tool.

## Raspberry Pi 

2019-09-26-raspbian-buster-full.img

## Node RED

