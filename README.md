#Introduction
In this project, I will be making a SketchBoard/Etch-A-Sketch. The functionality of this board is that a user is able to sketch, save, and view a drawing. The sketching involves being able to move anywhere on the board(screen), draw anywhere and erase any part that the user would like.

The board functionality includes using buttons to control a menu, and using the joystick to sketch onto the Nokia 5110 LCD Screen, with the ability to erase and also save drawings in EEPROM, so even after the machine turns off, the previous saves, can be loaded up by using the view functionality implemented. 

My complexities include and new technology learned:

Nokia 5110 Screen, this complexity was not taught in class, so therefore in order to get the machine function, I was able to find an existing library and add my own code to it, in order to use the lcd for sketching purposes. 

Analog Joystick, this was also not taught in class, in order to get the joystick to function I learned about ADC, and how we can use the ADC embedded on the microcontroller and use multiple ADC pins. In order to get the joystick function properly, I found a library for the adc use, I learned from it and created my own adc_read function.

Custom Character, this was a functionality used on the 16x02 LCD Screen, and I got help from ElectronicWings Website, and used it as a reference to create my own custom character selection tools. I learned that you can assign each pixel on one location for the lcd to create a custom character.

EEPROM, I learned to use the EEPROM library that is already included, and found out how to assign arrays and create memory on the microcontroller and how to read and write to a location onto the microcontroller. 


##Technologies and Components used

Nokia LCD 5110 Screen
Analog 2 Axis Joystick with button
16 x 02 LCD Screen
Atmel Studio 7.0
Atmega1284
2 Buttons
Potentiometer
