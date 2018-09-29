Author: Shane Price
Last Edited: 09/28/18

# Button Interrupt
This part of the lab the task was to switch the led that is on when the a button was pressed. This was done on two different boards, the MSP430G2553 and the MSP430FR2311. This was done by using interrupts, when the button was pressed the interrupt activates and switches to the LED that was previously not on and turns the one that was on off. Then the flag is cleared and waits until the button/interrupt coccurs again. 

## Inputs/Outputs
### MSP430G2553
Inputs: P1.1-Button
Outputs: P1.0 LED, P1.6 LED
### MSP430FR2311
Inputs: P1.3-Button
Outputs: P1.0 LED, P2.0 LED
