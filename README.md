# car_sensor

Parking distance sensor based on STM32F103C8T6 (bluepill) and ultrasonic ranging module HC-SR04.

Parts used for the project:
- bluepill
- ultrasonic ranging module HC-SR04
- perf boards (5cm x 7cm and 2cm x 8cm)
- 9 LEDs (4 green, 3 yellow, 2 red)
- passive buzzer
- resistors: R1-9x22kOhm, R2-9x100Ohm, R3-1x10kOhm
- 10 2n2222 bjt transistors
- step up converter
- LP2950L-3.0 voltage stabilizer
- 3,7V liion battery
- 2 lever switches

## Circuit diagram
![circuit_diagram2](https://user-images.githubusercontent.com/50926917/195899854-2f93d8c8-aa93-4b6f-ac7e-031f0b7524ff.png)

## Features
* 9 programmable threshold distances for activating LEDs and buzzer beepingfrequency
* buzzer increases frequency of beeping the closer the object is
* buzzer programmable turn off time (default 7 seconds) after reaching 2nd closest threshold distance
* LEDs programmable tunr off time (default 15 seconds) after reaching closest threshold distance

## Project result

https://user-images.githubusercontent.com/50926917/195894758-f9a88620-6a1d-4caf-b80c-9c7bcadc3a5a.mp4

![IMG_7661](https://user-images.githubusercontent.com/50926917/195894881-3d54f708-f250-4389-818b-b17fd596cbd0.JPG)


