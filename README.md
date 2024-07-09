# ESP32 LED Control with Button Press
This project demonstrates a simple circuit using the ESP32 microcontroller, where an LED turns on when a button is pressed. The code provided here sets up the ESP32 to monitor a button state and control an LED accordingly.

## Introduction
This repository contains the code to implement a basic interaction between a button and an LED using the ESP32 microcontroller. The LED connected to pin 2 lights up whenever the button connected to pin 34 is pressed. This is a simple example to demonstrate digital input and output handling on the ESP32 platform.

## Hardware Requirements
- ESP32 development board
- 1 LED
- 1 Pushbutton
- Resistors
- Breadboard and jumper wires

## Software Requirements
- Arduino IDE

## Circuit Diagram
![image](https://github.com/Mjd0001/simple_esp32_circuit/assets/105239889/78d88e4a-4ec3-4535-b597-4fb3b999951f)

## Setup Instructions
1- Download or Clone the Repository.

2- Open in Arduino IDE:

3- Open the esp32_code.ino file from the cloned repository.
4- Install ESP32 Board Support:

1- File => Preferences => Paste this in "Additional Boards Manager URLs: https://dl.espressif.com/dl/package_esp32_index.json
2- Tools => Board => Boards Manager => search "ESP32" then Install it.
3- Connect ESP32 to the computer.
4- Choose The Board: Tools => Board => ESP32 Arduino => WEMOS D1 MINI ESP32.
5- To Test The ESP32: File => Examples => Basics => Blink
6- Upload the code
7- Then the LED in the ESP32 will Blink, that's mean it's work well.

5- Upload The Code.

## Usage
Once the code is uploaded successfully. Press the button connected to pin 34; the LED connected to pin 2 should turn on.
Release the button to turn off the LED
