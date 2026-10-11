# BCA188 Laboratory 3: GPIO and Button Control

This laboratory demonstrates GPIO input and output control using an ESP32, a push button, and two LEDs. The second LED displays the opposite state of the first LED.

## Source Code
- GPIO and Button Control – ESP32
- Push button configured using `INPUT_PULLUP`
- Two LEDs operating in opposite states
- GPIO input reading using HIGH and LOW

## Circuit Connections
- Push Button – GPIO23 and GND
- LED 1 – GPIO18
- LED 2 – GPIO19

## Observed Results

| Button State | Input Reading | LED 1 | LED 2 |
|---|---|---|---|
| Released | HIGH | OFF | ON |
| Pressed | LOW | ON | OFF |

The circuit successfully demonstrated opposite LED states and stable button input.

## Laboratory Report
[View Laboratory 3 Report](Martin_Laboratory3_Report.pdf)
