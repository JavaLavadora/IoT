# IoT

In order to be able to use the arduino IDE with this microcontroller add the following library in File/Preferences (or Arduino/Preferences on Mac):
http://arduino.esp8266.com/versions/2.3.0/package_esp8266com_index.json

Then go to Tools/Boards/Board Manager then look for the ESP8266 library and add it

Note: In order for the correct port to appear on mac, a driver must be installed
    Find it in: http://kig.re/2014/12/31/how-to-use-arduino-nano-mini-pro-with-CH340G-on-mac-osx-yosemite.html
    
Configurations:

- Standard: regular connection of the microcontroller to a wifi network
    Control: through url of the form ip_address/digital/pin_number/value_for_pin
  
- Blynk: connection through blynk.
    Control: through blynk app
    Usage:
        1.Add blynk library
        2.Use ESP8266_Standalone example (same code)
    http://www.blynk.cc/
