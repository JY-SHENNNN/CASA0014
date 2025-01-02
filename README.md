# CASA0014 


https://github.com/user-attachments/assets/a73fa6aa-9c91-4124-bc7d-2995820d4178


## Interact with Internet of Things (Overview)
The Chrono Lumina light enhances user interaction with IoT systems by using touch sensors for intuitive control, creating dynamic lighting that reflects real-time activities in the lab. This responsive system encourages experimentation and creativity, fostering engagement and exploration while promoting a collaborative and innovative environment.

<div style="display: flex; justify-content: space-between; align-items: center;">
  <img src="https://github.com/JY-SHENNNN/CASA0014/blob/main/src/allchronoLumina.jpg" alt="Left Image" width="400">
  <img src="https://github.com/JY-SHENNNN/CASA0014/blob/main/src/finalenclo.jpg" alt="Right Image" width="400">
</div>

## Inspiration
* To enhance user interaction with the IoT system, aimed to select a sensor that is both intuitive and meaningful for users. Touchpads provide a natural and effortless way to interact, making them easy to use without requiring prior training. Their ability to detect various gestures, such as taps, swipes, and long presses, adds a layer of interactivity that aligns well with the dynamic nature of IoT systems. This versatility not only simplifies user engagement but also fosters a deeper connection with the system, allowing users to focus on exploration and creativity. Inspired by the need for an accessible and responsive interface, I chose the touchpad as the core input method for this project.
* During the tour in science museum, environmental lighting plays a crucial role in creating a strong sense of immersive experience. Each exhibit is complemented by unique lighting, designed to evoke specific emotions and resonate with the story it tells. Just as every exhibit conveys a distinct narrative, lighting brings out its essence, allowing viewers to connect emotionally. This concept inspired me to use dynamic lighting in my project, reflecting user interactions and creating an environment where each action or idea reveals a unique visual response, much like how exhibits in the museum reveal their stories through light.

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

## Interaction Mode
The general idea is to use two touchpads to control the chrono lumina, which reflects the current thinking in mind.
* single click: No idea or offline
  - single click 1: turn on the default light
  - single click 2: turn off the all light
* double click: researching or brainstorming to complete
  - double click 1: all random
  - double click 2: dynamic 12 color circuit
* swipe: more clearer idea or idea but with problem
  - from 2 to 1: decrease brightness
  - from 1 to 2: increase brightness




## Reference
1. The electronic graph pruduced by Fritzing
   * the Arduino mkr1010 wifi part found through[ https://forum.fritzing.org/t/pine-a64-esp8266-12e-f-arduino-zero-and-mkr1000-new-fritzing-parts/1611](https://forum.fritzing.org/t/part-request-arduino-mkr-wifi-1010/7617/2)
   * the touch sensor part found through https://forum.fritzing.org/t/ttp223b-module-alternative-design/11139/2
