# DOT-hardware

## Requirements

### Board

* ESP8266 on a D1 mini
* PN532
* custom RGB board

### libraries 

* some way of flashing code to the board (e.g. Arduino IDE)
* (todo) libraries
  
## Installation

* Either use the library directory in the repo or copy the files to your
  Arduino/libraries/ folder 
* configure your setup for your board:
  
  - Add http://arduino.esp8266.com/stable/package_esp8266com_index.json to your
    Additional Boards Manager URL
  - Download the ESP8266 boards
  - choose board 'WeMos D1 R1' 
  - set up the correct port

## ToDo

* finish readme
* implement connection with backend
