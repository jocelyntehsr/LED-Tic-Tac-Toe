# LED-Tic-Tac-Toe

LED Tic Tac Toe that is in dual-player mode can be constructed using the following board and components:

-STMicroelectronics Nucleo-F411RE board

-9 Red LEDs

-9 Blue LEDs

-18 220ohm resistors

-2 pushbuttons

-LCD Display

-Male to male jumping wires

# Arrangement
The LED should be arranged as follow:

![image](https://user-images.githubusercontent.com/84454650/118826362-01fcbd00-b8ee-11eb-955b-2e9d5be2f153.png)


# How to Play
Each player uses a different coloured LED to place their mark. 

There are two pushbuttons, in which one is used to select the position of LED while the other one is used to lock the position of LED.

One pushbutton is used to Select the position to mark and another pushbutton is used to Lock the choice. 
The Select button is used to move from one LED to another from position 1 to position 9, for the player to Select.
The LED that is currently up for selection will blink ON and OFF. 

The player locks his selection  by pressing the Lock button, and the LED in that position will stay ON. The next player is then
allowed to choose his position to mark using the LEDs of the second colour. A player cannot
mark a position that has been marked previously. Each position can only have one of the two
colours marked.

Once a line is formed by three LEDs of the same colour (regardless of horizontally/ diagonally/ vertically), then the LCD display will indicate that the player wins while the game will be restarted.

# Demonstration 

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/4O0Vv9Xb9yI/0.jpg)](https://www.youtube.com/watch?v=4O0Vv9Xb9yI)
