# nodemcu


This is a file with instructions on writing ESP8266 code to a NodeMCU

1. Download the arduino IDE.
2. [Linux Only] Add current user to dialout group : `sudo usermod -a -G dialout USERNAME`. Log out and log back in to apply.
3. Open File Menu > Preferences and paste `http://arduino.esp8266.com/stable/package_esp8266com_index.json` in the Additional Board Managers URL field.
4. Open Tools Menu > Board > Board Manager, search for esp8266 and install the package.
5. Open Sketch > Include Library > Manage Libraries, search for the DHT esp8266 library, if needed, and install that too.
6. Try out an example. File > Examples > ESP8266 > Blink
7. NOTES: In Tools Menu, for the options,
    - Select a baud rate of 115200
    - **DO NOT SELECT ALL FLASH CONTENTS WHEN ERASING FLASH**.
    - Select the appropriate /dev/tty0 or COM* port.
8. Click compile. Then Click upload.
9. The LED should be blinking constantly after upload for the blink.ino example.