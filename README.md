# wifie-esp32
Setup Initial Wifi on esp32 or esp8266
### Install the correct drives : 
1. Download from here [CP210x Drivers ]([https://website-name.com](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads)
2. On Windows - open the Device Manager, look for the CP210 drivers above the COM ports
3. Click on update driver ( you will see the yellow triangle telling you the driver is not happy)
4. Click on browse for drivers , select the drivers you just downloaded.
5. It will show up with a COM port - it was 12 in my case.

### Setup Arduino IDE for ESP32:
1. Click on File, select preferences , add the following URL under Addtional Board Manager URLs to include the ESP boards:
2. ```https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json, http://arduino.esp8266.com/stable/package_esp8266com_index.json```
3. Click on the boards manager ( the panel on the left if you are using IDE 2, Under tools for Arduino Studio)
4. Install either the 8266 or 32 board
5. Select the correct board and port and upload your sketch.

