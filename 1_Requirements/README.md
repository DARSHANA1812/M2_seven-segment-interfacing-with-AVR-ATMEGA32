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
*   7 Segment display
*   push switch
*   Power Supply

## SWOT Analysis
__STRENGTH__
*   It provides a convenient way of displaying numerical information from zero to nine .
*   cost of leds are cheap.
*   Realibility, efficiency, production. 

__WEAHNESS__
* Most seven segment display are limited to displaying the 16 hexadecimal characters.
* Seven-segment displays are limited to possible binary combinations of the four input leads,for a total 0f 16. 

__OPPORTUNITIES__
*The 7-segment display, also written as “seven segment display”, consists of seven LEDs (hence its name) arranged in a rectangular fashion as shown. Each of the seven LEDs is called a segment because when illuminated the segment forms part of a numerical digit (both Decimal and Hex) to be displayed.

__THREATS__
* This is the most challenge seven segment display are limited to displaying the 16 hexadecimal characters ,Seven-segment displays are limited to possible binary combinations of the four input leads,for a total 0f 16.

## 4W'S and 1'H
__WHO__
This will be useful to convenient way of displaying numerical information

__WHAT__
The main aim  of this project is to A seven-segment display is a form of electronic display device for displaying decimal numerals that is an alternative to the more complex dot matrix displays. Seven-segment displays are widely used in digital clocks, electronic meters, basic calculators, and other electronic devices that display numerical information .

__WHEN__
This will be useful to when illuminated the segment forms part of a numerical digit (both Decimal and Hex) to be displayed .

__WHERE__
This will be working in According to the type of application, there are two types of configurations of seven segment displays: common anode display and common cathode display. In common cathode seven segment displays, all the cathode connections of LED segments are connected together to logic 0 or ground.

__HOW__
The straightforward way to do that is to connect each pin from the seven-segment to a pin on the MCU and use the software to control the LEDs lighting and display the numbers we want. However, this way is not efficient as it wastes a lot of valuable MCU pins

## Detail Requirements 
__High Level Requirements__
| ID | Description | Status |
| -- | ----------- | ------ |
| HLR1 | seven-segment display | provides a convenient way of displaying numerical information |
| HLR2 | Atmega 32 | Microcontroller used for the entire process |
| HLR3 | Source Code | Used for the Execute the system |

__Low Level Requirements__
| ID | Description | Status |
| -- | ----------- | ------ |
| LLR1 | resistors | Used to protect the leds |
| LLR2 | display  | Used for the output calculations |
