# LoRa Based Underwater Wireless Network System

This repository contains the code of LoRa transmission that is used by paper N. Z. Nabhan and J. Suryana, "LoRa Based Underwater Wireless Network System," 2024 10th International Conference on Wireless and Telematics (ICWT). The manuscript is available on [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10674681). 

## Dependencies
- Arduino IDE or PlatformIO for compiling and uploading code to the board
- LoRa E32 library for Arduino (available at [https://github.com/xreef/LoRa_E32_Series_Library](https://github.com/xreef/LoRa_E32_Series_Library))

## Installation
1. In Platform IO, open the file `LoRa_Transmit_Arduino` for the transmitter and `LoRa_Receiver_Arduino` for the receiver.
2. Add the following to your platformio.ini
```bash
lib_deps = xreef/LoRa_E32_Series_Library
```
3. Build and upload code to ESP32



