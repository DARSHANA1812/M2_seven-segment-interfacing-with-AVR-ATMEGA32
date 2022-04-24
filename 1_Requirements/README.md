# M2_seven-segment-interfacing-with-AVR-ATMEGA32

# Requirements
## Introduction
The main Aim of this project is the 7-segment displays are made up of 8 LED segments. 7 of these LED segments are in the shape of a line, whereas 1 segment is circular. The 7 line-shaped LED segments are used for displaying numbers 0 to 9 and a few letters like A, c, d, e, F, H, L, O, P, U, etc. The circular segment is used for displaying a decimal point.Each of the 8 elements has a pin associated with it which can be driven HIGH or LOW according to the type of display and the number or alphabet to be displayed.The common anode and common cathode types are available in a 7-segment display. Depending on which type is used, the control signal required to light up a segment in the display changes. Common anode requires a LOW signal whereas common cathode requires a HIGH signal to light up a segment.
## Research
In this project The Seven-segment consists of 7 LEDs arranged in a way that allows constructing a display of the numbers of (0-9). It has 10 pins assigned as follows:

7 pins act as the Vcc for the 7 LEDs (1 pin for each LED, assuming that we are dealing with common cathode seven segment display)
1 pin is the VCC for decimal point display at the lower right corner.
2 pins represent a common ground to all the LEDs.

## Defining our project
There are 2 types of seven-segment, that are “common anode” and “common cathode”. In common anode seven segment, VCC is common for all the LEDs and each has a different pin for the low voltage (that is ground). In the case of a common cathode, all LEDs have a common ground and each has a different pin for the high voltage (Vcc). In this tutorial, we will be using a common cathode 7 Segment display.

Interfacing 7 Segment Display with AVR Atmega32:
The straightforward way to do that is to connect each pin from the seven-segment to a pin on the MCU and use the software to control the LEDs lighting and display the numbers we want. However, this way is not efficient as it wastes a lot of valuable MCU pins. Imagine that you want to connect 2 seven-segment devices to display the numbers (0-99), in this case, you will need to use 14 pins of the MCU I/O pins which may leave you in a shortage of pins for other external peripherals

## Features
*   Available in two modes common cathode and comoon anode.
*   Available in many different sizes .
*   Available colours like blue,red,green etc.,  .
*   lower current operation

__Components Used__
*   Atmega32
*   Resistors
*   Segment display
*   Switches
*   Power Supply

## SWOT Analysis
__STRENGTH__
*   It work like an alert system for the blind people.
*   It is   cheaper than compared to the existing system .
*   The LCD out available in this project makes the  people to detect  of the  opposite objects .
  
__WEAKNESS__
*   It gives only the information of the opposite objects only.
*   Due to we used only one ultra sonic sensor This gives only information of lesser distance.

__OPPURTUNITIES__
*   There will be no need for the dependent to go outside.
*   The updation of the projects will be we have to give some specifications like 360 degree assistance .
*   We also make this glasses for the reading purpose also *Smart Glass For the Blind* with some added specifications.
 
__THREATS__
*   The major challenges is There will be an Battery backup .If they go for some long distance then battery backups is concerned .

## 4W'S and 1'H
__WHO__
This will be useful to an the blind peoples.

__WHAT__
The main aim  of this project is to reduce the dependencies of the other people of blind peoples .

__WHEN__
This will be useful to them when they go outside and whenever they need assistance . .

__WHERE__
This will be working in every where .This also works in rainny days and winter also.

__HOW__
The sensor used in this project Ultrasonic sensor which detects the opposite objects and send this information to the microcontroller then it gives the message to the user.
## Detail Requirements 
__High Level Requirements__
| ID | Description | Status |
| -- | ----------- | ------ |
| HLR1 | UltraSonic Sensors | Used for the sensing the objects |
| HLR2 | Atmega 328p | Microcontroller used for the entire process |
| HLR3 | Source Code | Used for the Execute the system |

__Low Level Requirements__
| ID | Description | Status |
| -- | ----------- | ------ |
| LLR1 | Buzzer | Used for the output of the Microcontroller |
| LLR2 | Glass | Used  as  support for the sensor |
| LLR3 | LCD   | Used for the output calculations |
