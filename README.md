# Circuitmess Arduino packages
This repo contains platforms and board definitions for CircuitMess' devices.

Archives containing platforms can be found on the [releases page](https://github.com/CircuitMess/Arduino-Packages/releases). The package indexes are commited to the repo.

## Devices
* ESP32: Ringo, Spencer, Jay-D, Wheelson, ByteBoi, Chatter, Chatter 2.0, CircuitPet, Batmobile & 
  BatController, Armstrong, Clockstar
* ESP8266: Nibble

# Installation
You can install the platforms using the Arduino IDE:

* Open the Arduino IDE
* Go to File -> Preferences
* Under **Additional board Manager URLs** add the URLs to the desired platform indexes, separated by line breaks
  * ESP32: https://raw.githubusercontent.com/CircuitMess/Arduino-Packages/master/package_circuitmess.com_esp32_index.json
  * ESP8266: https://raw.githubusercontent.com/CircuitMess/Arduino-Packages/master/package_circuitmess.com_esp8266_index.json
* Close the preferences by clicking OK
* Open the Board Manager under Tools -> Board -> Boards Manager...
* Type 'CircuitMess' in the search bar
* Click the Install button on the packages you want to install
