# BlueTooth_Beacon
Libraries and codes to send bluethooth beacon and data from ESP32 and raspberry pi. Also arduino source codes.

Raspberry Pi Codes to scan bluetooth devices


install bluez
```
sudo apt-get install python3-pip libglib2.0-dev
sudo pip3 install bluepy
```

check bluetooth
```
hciconfig
```
scan 
```
 sudo hcitool lescan
```
to switch on the Raspberry Pi’s Bluetooth device, you can utilize the following command.
```
sudo hciconfig hci0 up
```
switch on the Low Energy Advertising mode, and set it to the Nonconnectable undirected advertising mode.
```
sudo hciconfig hci0 leadv 3
```
Important liabraries and sources from Niel Kolban
ESP32 BLE library 
```
https://github.com/nkolban/ESP32_BLE_Arduino.git
```
# ESP32 BLE for Arduino (This repository is kept for archive. BLE code is now included in Arduino directly.)
The Arduino IDE provides an excellent library package manager where versions of libraries can be downloaded and installed.  This Github project provides the repository for the ESP32 BLE support for Arduino.

The actual source of the project which is being maintained can be found here:

https://github.com/nkolban/esp32-snippets

Issues and questions should be raised here:

https://github.com/nkolban/esp32-snippets/issues


Documentation for using the library can be found here:

https://github.com/nkolban/esp32-snippets/tree/master/Documentation
