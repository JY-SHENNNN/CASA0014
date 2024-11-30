There are the code which have been used in sketch, test and finalisation.
# Task
This project steps into 3 parts:
1. make wifi connection through MQTT and Arduino
2. use touchpad to detect touch and transmit to Arduino
3. light mode control
After these three individual parts, it combines to a completed version, through the touchpad to control the Chrono Lumina.

# Instruction
The corresponding filename shows the related code:
* `touchdetect01` and `touchpad00` are used to generate the touch data
*  `connectLumina` and `arduino_secrets.h` are used to connect wifi
*  `test` is the first combined script to test if the color of the Chrono Lumina can be changed through the code
*  `version00`-`version03` are all the scipts used for integration. `version03` are the final integrated version 
