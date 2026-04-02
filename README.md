# alarm-timer-4-digits-7segment-display
This project show how to make an alarm timer with a 4 digits 7 segment display. The user can input a number from 1 to 9999 in the terminal of the computer (in seconds) and the buzzer will beep once that time is over.
. The materials you will need for this project.
1x arduino board
1x active buzzer
8x 1000 ohm resistors
jumper wires
brearboard
4 digits 7 segment display
.
Connect each digit pins without a resistor to a digital pin in the arduino. There are 4 digits D1, D2, D3, D4 and each will connect to a digital pin in the arduino without a resistor. 
Then connect all the segments pins to a respective resistor and then to the digits pins, there will be in total 8 segment pins including the Decimal point which we will not use but you can according to your personal needs.
To help you connect the wires of the display this is a diagram of the 4 digits 7 segment display

<img width="695" height="518" alt="image" src="https://github.com/user-attachments/assets/c1109c30-6a21-47f2-aa6d-1abdd88bb099" />
