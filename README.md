# BlueTooth_Beacon
Libraries and codes to send bluethooth beacon and data from ESP32 and raspberry pi. Also arduino source codes.

Raspberry Pi Codes to scan bluetooth devices


---install bluez
sudo apt-get install python3-pip libglib2.0-dev
sudo pip3 install bluepy

---check bluetooth

hciconfig

----scan 

 sudo hcitool lescan

to switch on the Raspberry Pi’s Bluetooth device, you can utilize the following command.

sudo hciconfig hci0 up

switch on the Low Energy Advertising mode, and set it to the Nonconnectable undirected advertising mode.

sudo hciconfig hci0 leadv 3
