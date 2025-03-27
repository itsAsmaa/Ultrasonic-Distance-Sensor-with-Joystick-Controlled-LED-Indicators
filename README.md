# Ultrasonic Distance Sensor with Joystick-Controlled LED Indicators

## Overview

This project demonstrates how to use an ultrasonic distance sensor (HC-SR04) along with three LEDs (green, yellow, and red) to display distance measurements and indicate proximity. The distance thresholds that control which LED is activated are adjustable in real-time using a joystick. The system measures the distance, compares it to adjustable thresholds, and activates the appropriate LED.

https://trello.com/c/WiBFNgrZ/15-https-youtube-ltarkd0h42efeatureshared

### Features:
- Measures the distance using an ultrasonic sensor (HC-SR04).
- Controls three LEDs based on the distance:
  - **Green LED**: Activated when the distance is greater than or equal to the green threshold.
  - **Yellow LED**: Activated when the distance is between the yellow and green thresholds.
  - **Red LED**: Activated when the distance is less than the yellow threshold.
- Joystick-controlled thresholds for dynamic adjustment of distance thresholds.
- Debugging data (distance and threshold values) is printed to the Serial Monitor.

## Components Used:
- **Arduino Uno (or compatible)**
- **HC-SR04 Ultrasonic Distance Sensor**
  - Trigger Pin: Pin 11
  - Echo Pin: Pin 10
- **Joystick Module**
  - X-axis Pin: A4
- **LEDs**:
  - Green LED: Pin 5
  - Yellow LED: Pin 4
  - Red LED: Pin 3

## Wiring Diagram:

- **Ultrasonic Sensor**:
  - `Trig Pin` → Pin 11
  - `Echo Pin` → Pin 10

- **Joystick**:
  - `X-axis Pin` → Pin A4

- **LEDs**:
  - Green LED → Pin 5
  - Yellow LED → Pin 4
  - Red LED → Pin 3


