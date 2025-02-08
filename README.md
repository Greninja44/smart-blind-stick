# Ultrasonic Distance Sensor with Buzzer and LED Alert

This project uses an ultrasonic sensor (HC-SR04) to measure the distance of an object and triggers a buzzer and LED when the object is too close (within 10 cm). It’s a simple safety distance detection system.

## Components Needed:
- Arduino Board (e.g., Arduino Uno)
- HC-SR04 Ultrasonic Distance Sensor
- Buzzer
- LED
- Jumper Wires
- Breadboard (optional)

## Circuit Diagram:
- **HC-SR04 Ultrasonic Sensor:**
  - `Trig Pin` → Pin 9
  - `Echo Pin` → Pin 10
  - `VCC` → 5V
  - `GND` → GND
- **Buzzer:**
  - Connect one pin to Pin 11 and the other to GND.
- **LED:**
  - Connect the long leg (anode) to Pin 13 and the short leg (cathode) to GND through a 220Ω resistor.
