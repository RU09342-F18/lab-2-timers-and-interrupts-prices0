Author: Shane Price
Last Edited: 09/28/18

# Button Based Delay
This part of the lab the task was to have an LED blink at a rate corresponding to how long a button was pressed. IE hold the button for 2 seconds the LED blinks once every 2 seconds. This was done on two different boards, the MSP430G2553 and the MSP430FR2311. 

This was done by initially having the LED blink at a specified rate then would change on the interrupt, button press. When the button was pressed the interrupt begins and a timer begins to count the amount of time it is held down for, then once the button is released the timer turns off and the time is stored, timer is reset, set back to up mode from contniuous mode of counting the time, the interrupt flags are reset as well. At this time the LED blinks at the rate corresponding to the length of time the button was pressed for, as explained above. 

## Inputs/Outputs
### MSP430G2553
Inputs: P1.1-Button
Outputs: P1.0 LED
### MSP430FR2311
Inputs: P1.3-Button
Outputs: P1.0 LED
