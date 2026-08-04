# Ultrasonic Sensor and Servo Motor Control Using Arduino

## Project Description
This project demonstrates the control of a **Servo Motor** using an **HC-SR04 Ultrasonic Sensor** and an **Arduino Uno**.  
The ultrasonic sensor measures the distance between the sensor and an object. Based on the detected distance, the Arduino controls the servo motor position.

When an object is detected within a specific distance, the servo motor rotates to a defined angle. When the object moves away, the servo returns automatically to its original position.

---

## Components Used
- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- Servo Motor
- Breadboard
- Jumper Wires
- USB Cable

<img width="120" height="231" alt="image" src="https://github.com/user-attachments/assets/4189900c-2236-48ff-a5db-f44dfb0eadf5" />


## System Operation
1. The HC-SR04 ultrasonic sensor sends ultrasonic waves and receives the reflected signal.
2. The Arduino calculates the distance based on the echo time.
3. If the object is within the activation distance, the servo motor rotates.
4. If the object moves farther than the specified distance, the servo returns to 0°.
### Code in file (Code)

## Experiment: Testing Different Servo Angles and Distances

To observe the effect of changing parameters, different servo angles and activation distances were tested by modifying the values in the code.

### Experiment 1: Servo Angle 45° and Distance 15 cm
file Code2

### Experiment 2: Servo Angle 180° and Distance 15 cm
file Code3

# Experimental Results
45° Angle:
The servo motor rotates a small movement when an object is detected at a distance of 15 cm or less.
90° Angle:
The servo motor rotates approximately half a turn when an object approaches.
180° Angle:
The servo motor rotates to its maximum angle when an object is detected.
When the object moves farther than 15 cm, the servo motor automatically returns to the initial position (0°) in all experiments.
