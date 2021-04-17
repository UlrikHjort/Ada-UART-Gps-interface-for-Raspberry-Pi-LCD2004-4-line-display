# Ada UART Gps interface for Raspberry Pi LCD2004 4 line display 

Ada UART gps interface for Raspberry Pi for reading Time, Latitude and Longitude. Tested with Gps module ZHITING NEO-7M UBLOX (with external antenna) and Gps module Aideepen GY-GPS6MV2 NEO-6M. Should be working though with an arbitrary UART Gps module delivering data in NMEA 0183 format.

## Hardware:
* LCD2004 HD44780 4x20 5x7 LCD display
* Raspberry Pi 3 Model B+
* Gps module ZHITING NEO-7M UBLOX
* Gps module Aideepen GY-GPS6MV2 NEO-6M 
* GPS antenna 1575.42MHz-3MHz / 1575.42MHz+3MHz 

## Wiring:
UART0 is used.

| UART Gps Module  |  Raspberry Pi PIN |
| --- | --- |
|GND | GND |
|VCC | +3.3V |
|TxD | GPIO14 (UART0 TxD) |
|RxD | GPIO15 (UART0 RxD) |
|PPS (Only NEO-7M) | Not Connected |


Ada version >= ada2012 used


(Yes, position data on attached picture had been modified to not show my actual location)
