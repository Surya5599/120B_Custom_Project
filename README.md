# SKETCHBOARD EMBEDDED SYSTEMS

## Introduction

In this project, I will be making a SketchBoard/Etch-A-Sketch. The functionality of this board is that a user is able to sketch, save, and view a drawing. The sketching involves being able to move anywhere on the board(screen), draw anywhere and erase any part that the user would like.

The board functionality includes using buttons to control a menu, and using the joystick to sketch onto the Nokia 5110 LCD Screen, with the ability to erase and also save drawings in EEPROM, so even after the machine turns off, the previous saves, can be loaded up by using the view functionality implemented. 

My complexities include and new technology learned:

Nokia 5110 Screen, this complexity was not taught in class, so therefore in order to get the machine function, I was able to find an existing library and add my own code to it, in order to use the lcd for sketching purposes. 

Analog Joystick, this was also not taught in class, in order to get the joystick to function I learned about ADC, and how we can use the ADC embedded on the microcontroller and use multiple ADC pins. In order to get the joystick function properly, I found a library for the adc use, I learned from it and created my own adc_read function.

Custom Character, this was a functionality used on the 16x02 LCD Screen, and I got help from ElectronicWings Website, and used it as a reference to create my own custom character selection tools. I learned that you can assign each pixel on one location for the lcd to create a custom character.

EEPROM, I learned to use the EEPROM library that is already included, and found out how to assign arrays and create memory on the microcontroller and how to read and write to a location onto the microcontroller. 


## Technologies and Components used

- Nokia LCD 5110 Screen
- Analog 2 Axis Joystick with button
- 16 x 02 LCD Screen
- Atmel Studio 7.0
- Atmega1284
- 2 Buttons
- Potentiometer

## User Guide

There are 2 buttons on the breadboard, the button on the left is to move selection on the 16 x 02 LCD Screen, the right button is to Select the selection you are on. For example on the main screen you can press the left Button to pick between Sketch or View, then chose that selection by pressing the button to the right of the LCD.

Sketch has multiple functionalities, Move, Draw, Delete, Save, Exit. When the selection icon is on the move, the user is able to move the cursor on the Nokia LCD anywhere on the screen using the joystick as a controller. User can press the button on the left of the 16x02, to switch the selection to Draw, in which, the user can draw on the cursor by moving the joystick. Delete selection will remove the drawing, where the cursor goes, so if user makes an error they can fix it but using Delete Selection. When on the Save functionality user can press the Select button, to save their current drawing in to 4 selections S1, S2, S3, S4. Exit can take the user back to the previous screen. 

View Selection allows the user to view their saved files from S1, S2, S3, S4. Using the change selection button and Select button, user can select between save files and load the one they want.

## Breadbaord Wiring and Configuration  
![GitHub Logo](/images/connections.png)

![Github Logo](/images/config.JPG)

## Link To Video

https://youtu.be/yTozSoyTcqY

## Future Work:

I want to continue developing the Sketchboard by creating a better Menu interface, and an easier and a much faster way to select options, because right now you have to toggle through many options to get to one. Next thing I would do it, introduce more saving options, so that a person could save a file they are working on and load up a drawing and continue with that drawing. Also an auto save functionality, so that if someone forgets to save, and turns off the machine, they can revive their work. 
