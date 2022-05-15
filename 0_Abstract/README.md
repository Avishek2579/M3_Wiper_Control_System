# **Wiper Control System**

## **1 About Wiper Control System**

## **1.1 Abstract**

A wiper is a necessary component that cleans raindrops or any other liquid off the vehicle's windscreen. The prior system required manual wiper activation, and the operation of bringing up the wiper was difficult to manage. As a result, this system is proposed to address these issues. The goals of this project are to provide wiping systems for older cars, to improve the system by employing actuators and pull switches (using the same switch for multiple purposes by stepwise switching), and to regulate the engine and wiper speed with a single switch.

In this project, we use the STM32F4xx-discovery board to illustrate an automobile wiper control system. Most automobile wipers are controlled by a DC motor, however because the STM32F4xx-discovery lacks a motor, we are exploring using LEDs in this application. As an example, the wiper control system. The STM32F4xx-discovery board has four LEDs and a Push Button. The colours of these LEDs are orange, green, red, and blue. A current limiting resistor connects four user LEDs to the PD12, PD13, PD14, and PD15 pins of PORTD on the Discovery board. To make a push button work with the STM32F407VG microcontroller, the GPIO pins will be set as digital input pins. If you push and hold the user button for two seconds, the Red When the ignition key is positioned at the ACC, the LED illuminates. Furthermore, the LEDs are flickering, indicating that the wipers are turned on.

## **1.2 Description**

Wiper Control System is an electronic device that replaces the traditional wiper blade in automobiles. In this system, we will use a single switch to control the ignition button (on the motor) in the ACC position. As a first press, turn on the wiper system by pressing the button a second time, change the wiper speed by pressing the button a third time, and turn off the motor by pressing the button a fourth time. All of this was accomplished using LEDs in a simulation tool.

## **1.3 Features**
  - ON The Motor(Ignition Position)
  - OFF the Motor
  - Power ON Wipers
  - Speed Controll of wipers

