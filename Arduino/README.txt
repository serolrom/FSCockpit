Model I purchased:
Search for ***** NODEMCU *****. Also ESP8266

BaseCode.ino code has been copied from https://www.youtube.com/watch?v=wkY1NsbWj5I&t=333s

- Install driver CH340
- Install Arduino software
- Install the following Arduino libraries. Menu Sketch->Include Library->Manage libraries; search and install the following ones, then INCLUDE them.
  - Joystick
  - Keypad
  
Next steps described in: https://create.arduino.cc/projecthub/electropeak/getting-started-w-nodemcu-esp8266-on-arduino-ide-28184f    
BOARD DEFINITION:
Arduino software needs to know this board definition, so we have to make it available for the software. For this:
- Go to File->Preferences->Additional Boards Manager URLs and insert this url:
  http://arduino.esp8266.com/stable/package_esp8266com_index.json
  
Now that the sofware knows where to get this board:
- Tools->Board->Boards manager. Search for ESP8266 and it will be found. Install.
- Select this board: Tools->Board->ESP Boards->NODEMCU 1.0

PORT:
Now the driver is also installed, go to Computer Mangement -> Device manager, search for Ports (COM & LPT). Note which port it is.0
In Arduino software: Tools->Port-> select the port.

------------------------------
Other references: 
https://www.youtube.com/watch?v=wkY1NsbWj5I&t=1197s (programming button matrix, but didn't make it work yet)





