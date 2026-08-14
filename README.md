## distance-based-servo

## Summary

The servo motor is driven and distance is measured by an ultrasonic sensor in this project. 
The servo swings to 180° if an object is detected within range; otherwise, it returns to 0°. 
A LED is turned on when an object is detected within range.

## Needs

Microcontroller (PIC family).

Ultrasonic sensor (HC-SR04, for example).

Servo motor.

LED to provide visual feedback.

Minimum electronics setup (wires, resistors, and a breadboard).

## Usage

Connect the ECHO pin and TRIG pin of the microcontroller to the ultrasonic sensor.

Connect the servo motor to the output pin of the microcontroller.

Add an LED for detection indication.

Upload the code to the microcontroller.

Power on the circuit.

According to the measured distance, the servo will turn:

180° if 2-10 cm.
0° otherwise.

## Example Output

Object detected within range → Servo turns to 180°, LED ON.

No object nearby → Servo rotates to 0°, LED OFF.

## Source Code
https://github.com/hexpad/DistanceBasedServo/blob/main/DistanceBasedServo.c
