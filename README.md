# Simple LED Blink Project with Arduino Uno

This is a beginner Arduino project where three LEDs blink on and off at the same time.

## What This Project Does

The program turns three LEDs on at the same time, waits two seconds, turns them off, waits two seconds, and then repeats continuously. It also prints "LED ON" and "LED OFF" to the Serial Monitor at 9600 baud.

## Components Needed

1 × Arduino Uno or compatible board
3 × LEDs
3 × 220Ω resistors
Breadboard
Jumper wires

## Pin Connections

LED1 is connected to pin 6.
LED2 is connected to pin 4.
LED3 is connected to pin 2.


<img width="941" height="747" alt="image" src="https://github.com/user-attachments/assets/c22aa161-010c-4ebb-930e-d865849bd4e9" />

Connect the long leg (anode) of each LED to the assigned Arduino pin through a resistor, and the short leg (cathode) to GND.

## How to Run

Open the code in the Arduino IDE, select the correct board and port, and upload the sketch. Open the Serial Monitor and set the baud rate to 9600 to see the status messages while the LEDs blink.
