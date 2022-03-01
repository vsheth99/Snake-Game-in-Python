# Snake-Game-in-Python
This is a basic snake game created using pygame in python
The first thing you will need to do in order to create games using Pygame is to install it on your systems 
pip install pygame

# Creating the screen

To create the screen using Pygame, you will need to make use of the display.set_mode() function. Also, you will have to make use of the init()  and the quit() methods to initialize and uninitialize everything at the start and the end of the code. The update() method is used to update any changes made to the screen. There is another method i.e flip() that works similarly to the update() function. The difference is that the update() method updates only the changes that are made (however, if no parameters are passed, updates the complete screen) but the flip() method redoes the complete screen again.
# Create the sanke
To create the snake, I will first initialize a few color variables in order to color the snake, food, screen, etc. The color scheme used in Pygame is RGB i.e “Red Green Blue”. In case you set all these to 0’s, the color will be black and all 255’s will be white. So our snake will actually be a rectangle. To draw rectangles in Pygame, you can make use of a function called draw.rect() which will help yo draw the rectangle with the desired color and size.
To move the snake, you will need to use the key events present in the KEYDOWN class of Pygame. The events that are used over here are, K_UP, K_DOWN, K_LEFT, and K_RIGHT to make the snake move up, down, left and right respectively. Also, the display screen is changed from the default black to white using the fill() method.

I have created new variables x1_change and y1_change in order to hold the updating values of the x and y coordinates.
