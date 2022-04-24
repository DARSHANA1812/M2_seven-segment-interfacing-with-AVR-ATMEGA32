# M2_seven-segment-interfacing-with-AVR-ATMEGA32

# Test Plan
## High Level Test Plan
| ID | Description | Ex I/P | Ex O/P | Actual Output |
| -- | ----------- | ------ | ------ | ------------- |
| HLT1 | Power On | Power supply | Display ON | PASS |
| HLT2 | Segment display | numbers In the range  | numbers detected | PASS |
| HLT3 | Output | Output of the segment | Displayed of numbers | PASS |

## Low Level Test Plan 
| ID | Description | Ex I/P | Ex O/P | Actual Output |
| -- | ----------- | ------ | ------ | ------------- |
| LLT1 | Numbers Range  | 0-9   | Numbers in range | PASS |
| LLT2 | Numbers Range  | above 9  | Numbers Not in range | PASS |

## Behavioural Diagram
![Behavioural diagram](https://user-images.githubusercontent.com/101334197/164954887-86d5b714-a764-47cc-81fe-075a7c1ae25c.jpeg)

## Block Diagram
![block diagram](https://user-images.githubusercontent.com/101334197/164954977-10258a8a-6e3c-4b41-afa6-ca943d2e4a60.png)

## Structural Diagram
![Structural diagram](https://user-images.githubusercontent.com/101334197/164955008-c123ca95-504d-4eb7-94ae-588301096801.jpeg)

