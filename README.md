# A small 1 Inch square Dice
This is a simple dice design using Microchip PIC12F1822 microcontroller.

## Notes
There is no any space left on the PCB for ICSP header.
Microcontrollers are programmed via a SOIC to DIP adapter and then are soldered to dice PCBs.
I am currently using another Microchip MCU (12F1822) rather than PIC12F629 used in the original design.

## Schematic
![Schematic snapshot](schematic.png)

## PCB (without copper pour)
![PCB snapshot](PCB.png)

## Assembled dice (Rev 1)
![Assembled board](Board.jpg)

# Credits
This project is more or less based on [Colin Mitchell's article](http://www.talkingelectronics.com/projects/LED%20Dice%20with%20PIC/Dice.html) for [Talking Electronics](https://en.wikipedia.org/wiki/Talking_Electronics) magazine. 

# To do
It would be much better to keep the PIC always powered on but in Sleep mode or Watchdog timer.
After switch is pressed, PIC should resume normal operation and roll the dice.
Then it could switch back to Sleep mode one minute after showing the result.
I have to study PIC12F1822 documentation to learn how to use it's Sleep mode.

# License
This hardware is licensed under [Creative Commons Share Alike](http://creativecommons.org/licenses/by-sa/4.0/).
