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
