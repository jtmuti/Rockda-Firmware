# Rockda Firmware Version History

## Application VER 3.7 (3.6.2018)
- Changed battery charging information for advertising data. Batt+1=charging Batt+2=charge complete
- UTC Time set feature via serial line (for production purposes)
- Main XTAL continuous operation while in BLE connection.

## Application VER 3.6 (28.5.2018)
- Added battery charging information for advertising data. Batt: 101=charging 102=charge complete
- FW version and error flags in advertising data.

## Application VER 3.5 (21.5.2018)
- Improved error reporting
- FW version and error flags in advertising data.

## Application VER 3.4 (21.4.2018)
* Advertising mem field show 1% if at least 100 bytes are collected in to flash.

## ApplicationVER 3.3 (11.4.2018)
* BLE disconnected if no data exchange within 15 sec

## Bootloader VER 4 (21.5.2018)
- Advertising as name "DfuPGD_<1-255>"
