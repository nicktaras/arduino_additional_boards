# arduino_additional_boards
How to program the ATTINY and ESP8266 boards with the Arduino IDE

Work in progress. 

// ESP package for Arduino IDE. Preferences > Additional Boards
http://arduino.esp8266.com/stable/package_esp8266com_index.json

// ATTINY58
https://raw.githubusercontent.com/damellis/attiny/ide-1.6.x-boards-manager/package_damellis_attiny_index.json

// Turning the Arduino into a Programmer.
http://highlowtech.org/?p=1706

1. Add the following to preferences > additional boards
https://raw.githubusercontent.com/damellis/attiny/ide-1.6.x-boards-manager/package_damellis_attiny_index.json

2. Add attiny by Davis A. Mellis library

3. Upload this example to the Uno, Examples > ArduinoISP

4. Change the programmer to - ISP for Arduino

5. Connect the attiny board using schematic

6. Add the following settings. 
- Set the board to ATTiny
- Set ATtiny85 to 8 MHz (internal) clock

7. Select burn bootloader

8. Upload sketch


