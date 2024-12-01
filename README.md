# CASA0014 

## Interact with Internet of Things (Overview)
The Chrono Lumina light enhances user interaction with IoT systems by using touch sensors for intuitive control, creating dynamic lighting that reflects real-time activities in the lab. This responsive system encourages experimentation and creativity, fostering engagement and exploration while promoting a collaborative and innovative environment.

<div style="display: flex; justify-content: space-between; align-items: center;">
  <img src="https://github.com/JY-SHENNNN/CASA0014/blob/main/src/allchronoLumina.jpg" alt="Left Image" width="400">
  <img src="https://github.com/JY-SHENNNN/CASA0014/blob/main/src/finalenclo.jpg" alt="Right Image" width="400">
</div>



## Interaction Mode
The general idea is to use two touchpads to control the chrono lumina, which reflects the current thinking in mind.
* single click: No idea or offline
  - single click 1: turn on the default light
  - single click 2: turn off the all light
* double click: researching or brainstorming to finish
  - double click 1: all random
  - double click 2: dynamic 12 color circuit
* swipe: more clearer idea or idea but with problem
  - from 2 to 1: decrease brightness
  - from 1 to 2: increase brightness

## Inspiration
- science museum environmental light -> stong sense of immersive experience
- differnet displayed item with differnt environmental lights -> creating emotional resonance
Every exhibit has a different story, just as our own experiences reveal different ideas

## Equipment
* Touchpad TTP223B
* Arduino MKR1010
* Jump wires

## System architecture
Touch Sensors (D2, D3) ->
Arduino MKR1010 WiFi ->
WiFi -> MQTT Broker -> Visualized Lights (Color, Brightness)
![](https://github.com/JY-SHENNNN/CASA0014/blob/main/src/flowchart.png)
![](https://github.com/JY-SHENNNN/CASA0014/blob/main/src/electronicCir.png)

## Reference
1. The electronic graph pruduced by Fritzing
   * the Arduino mkr1010 wifi part found through[ https://forum.fritzing.org/t/pine-a64-esp8266-12e-f-arduino-zero-and-mkr1000-new-fritzing-parts/1611](https://forum.fritzing.org/t/part-request-arduino-mkr-wifi-1010/7617/2)
   * the touch sensor part found through https://forum.fritzing.org/t/ttp223b-module-alternative-design/11139/2
