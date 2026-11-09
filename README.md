# Arduino Sonar Sensor LED Project

## 1. Project Overview

A beginner Arduino electronics project exploring ultrasonic distance measurement, digital inputs, and LED output control.

The project uses an ultrasonic sonar sensor to detect the distance between the sensor and an object. The measured distance is then used to control an LED output.

The project was based on an existing Arduino reference design, which was subsequently modified to incorporate an LED response.

### Objectives

- Understand how ultrasonic sensors measure distance.
- Learn how Arduino processes sensor readings.
- Explore the relationship between distance measurements and output control.
- Adapt an existing circuit to incorporate an LED indicator.
- Understand how sensors can be used in interactive electronic systems.

## 2. Hardware Specifications

| Component | Specification |
|---|---|
| Microcontroller | Arduino UNO R3 |
| Input | Ultrasonic sonar sensor [(Ultrasonic Sensor - HC-SR04]) |
| Output | LED |
| LED current-limiting resistor | [220 Ohms (Nominal)] |
| Prototyping | Breadboard and jumper wires |

## 3. Circuit Design

### Original Circuit

The initial circuit was based on an existing Arduino reference design featuring an ultrasonic sonar sensor.
### Modified Circuit

The original design was modified by incorporating an LED into the circuit.

The LED provides a visual output based on the distance measurements obtained from the ultrasonic sensor.

## 4. How It Works

### Ultrasonic Distance Measurement

The ultrasonic sensor emits a sound wave at a frequency beyond human hearing.

When the wave encounters an object, it is reflected towards the sensor.

The sensor measures the time taken for the sound wave to travel to the object and return. Arduino then uses this information to calculate the approximate distance.

### LED Output

The Arduino processes the distance measurement and controls the LED according to the programmed conditions.

- When the detected distance meets the programmed condition(Distance less than or equal to 20cm): LED [ON].
- When the detected distance does not meet the programmed condition(Distance greater than 20cm): LED [OFF].

The LED's behaviour depends on the distance threshold and conditions defined in the Arduino code.

## 5. Development and Modifications

The original circuit design and initial programming structure were obtained from Arduino reference resources.

The circuit was assembled and tested using an Arduino UNO R3 and an ultrasonic sonar sensor.

The following modifications were made:

- An LED was incorporated into the original circuit.
- The circuit connections were adapted to accommodate the additional LED.
- The original code was modified to integrate LED control based on the sensor's distance measurements.

AI-assisted guidance was used during the circuit and code modification process.

## 6. What I Learned

- How ultrasonic sensors detect objects and measure distance.
- How Arduino reads and processes sensor measurements.
- How to control an LED based on sensor input.
- How to adapt an existing circuit and program.
- How to assemble and test a sensor-based electronic system.

## 7. References and Acknowledgements

See [references/sources.md](references/sources.md)
for the original circuit and programming references.

AI tools were used as supplementary assistance when understanding and implementing circuit and code modifications.