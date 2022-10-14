# car_sensor

Parking distance sensor based on STM32F103C8T6 (bluepill) and ultrasonic ranging module HC-SR04.

# Table of contents
1. [Features](#features)
2. [Parts](#parts)
3. [Circuit diagram](#diagram)
4. [Results](#result)
5. [Mile stones](#phases)

## Features <a name="features"></a>
* 9 programmable threshold distances for activating LEDs and buzzer beeping frequency
* buzzer increases frequency of beeping the closer the object is
* buzzer programmable turn off time (default 7 seconds) after reaching 2nd closest threshold distance
* LEDs programmable tunr off time (default 15 seconds) after reaching closest threshold distance
* serial communication from uC (measured distance)

## Parts used for the project: <a name="parts"></a>
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

## Circuit diagram <a name="diagram"></a>
![circuit_diagram2](https://user-images.githubusercontent.com/50926917/195899854-2f93d8c8-aa93-4b6f-ac7e-031f0b7524ff.png)

Most left bottom uC pin is pin number 1 according to [this](https://microcontrollerslab.com/wp-content/uploads/2021/01/STM32F103C8T6-Blue-Pill-pinout-diagram.jpg) pinout scheme.
## Result <a name="result"></a>

https://user-images.githubusercontent.com/50926917/195894758-f9a88620-6a1d-4caf-b80c-9c7bcadc3a5a.mp4

![IMG_7661](https://user-images.githubusercontent.com/50926917/195894881-3d54f708-f250-4389-818b-b17fd596cbd0.JPG)

## Some phases of the project <a name="phases"></a>

![IMG_7488](https://user-images.githubusercontent.com/50926917/195903284-2c581efa-e2d6-47ab-8646-a5a8f409c5f8.jpg)
![IMG_7490](https://user-images.githubusercontent.com/50926917/195903293-c4baf59a-b578-49e4-9cb2-843dcf789078.jpg)
![IMG_7529](https://user-images.githubusercontent.com/50926917/195903294-dcf2f4ef-7506-4e6b-8bec-689187d31590.jpg)
![IMG_7538](https://user-images.githubusercontent.com/50926917/195903296-46073646-9d16-41d1-b7c2-0980b71bc7e8.jpg)
![IMG_7564](https://user-images.githubusercontent.com/50926917/195903299-35b5b8d2-b9ba-4245-900d-ad9afd646328.JPG)


