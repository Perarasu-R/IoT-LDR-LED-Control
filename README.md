# IoT Sensor-Based LED Control Using LDR

## Project Overview
This project demonstrates a simple IoT-based automatic lighting system using an Arduino Uno, an LDR (Light Dependent Resistor), and an LED. The system automatically turns the LED ON in low-light conditions and OFF in bright-light conditions. The project was designed and tested using the Tinkercad simulator.

## Objective
To simulate an IoT system where an LDR sensor detects light intensity and controls an LED automatically.

## Components Used
- Arduino Uno
- LDR (Light Dependent Resistor)
- LED
- 220 Ω Resistor
- 10 kΩ Resistor
- Breadboard
- Jumper Wires

## Software Used
- Tinkercad
- Arduino IDE (Arduino C/C++)
- GitHub

## Circuit Description
- LDR connected to Analog Pin A0.
- LED connected to Digital Pin 7 through a 220 Ω resistor.
- Arduino reads the LDR value and controls the LED based on light intensity.

## Working Principle
- The LDR senses ambient light.
- Arduino continuously reads the sensor value.
- In low light, the LED turns ON.
- In bright light, the LED turns OFF.

## Project Structure

```
IoT-LDR-LED-Control/
├── README.md
├── Arduino_Code.ino
├── Report.pdf
└── Screenshots/
    ├── Circuit.png
    ├── LED_ON.png
    └── LED_OFF.png
```

## Simulation Screenshots
Add your screenshots here after uploading them to the `Screenshots` folder.

## How to Run
1. Open the project in Tinkercad.
2. Start the simulation.
3. Adjust the LDR light level.
4. Observe the LED turning ON and OFF automatically.

## Author
**Perarasu R**

## Internship
CodeAlpha – Internet of Things (IoT) Internship
