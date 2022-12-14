# Tower of Hanoi
A Python program that solves the Tower of Hanoi problem for 3 to 12 disks and animates the solution.

## Dependencies
Assuming you have [Python3](https://www.python.org/downloads/) already, pygame, colour, and tkinter should be the only dependencies not automatically installed. They can all be installed with `pip`.
```
pip install pygame
pip install colour
pip install tkinter
```
## Usage
When running the program, a tkinter window opens first. Here you can change the number of disks using the arrow buttons. The number of disks can be between 3 and 12 inclusive. Check the color box to give color to the disks, otherwise all of the disks are white (the sole use of the colour library is to interpolate the colors based on the number of disks). When ready, press the start button. The program computes all of the neccesary moves before the pygame window opens. Since the number of moves is equal to 2<sup>n</sup>-1, the number of moves that the program calculates ranges from 7 to 4095. While the animation runs, you can change the delay and by proxy the speed of the animation using the up and down arrow keys (up is faster and down is slower). The number of disks, number of moves, and delay are shown in the window title.

![3](https://user-images.githubusercontent.com/68828123/184267345-77f41ce0-db6b-49ea-9a12-231ceb26e5cf.gif)
![8](https://user-images.githubusercontent.com/68828123/184267351-d451df8c-2c5e-4eaf-adc8-7d45b01086dd.gif)

