# PacMan

#Description
MIT xPro Coding Excercise

## Purpose
PacMan, an animated "ball" which changes the direction when it reaches the edge of the browser screen.

## Background
4 images of "PacMan": Orientation-mouth states: right-open, right-closed, left-open, left-closed.

Goal: HTML emdebbed animation of PacMan. Moves from the left to the right corner and returns back to the leftside. Since the pictures mouth-open/mouth-closed are switching it seems that PacMan is eating. Funcion Run makes it move. 

Function checkPageBounds makes sure, that the image/PacMan returns. 


# Installation
The code was tested on Google Chrome. Once loaded, the animation starts with a mouse click in the window. Clicking on the PacMan he becomes faster.


# Roadmap
For the exercise, the image can actually encroach over the boundary if the window size is not an even multiple of the image advancement. This was not a concern for the purpose of the exercise but to address it this code adds a buffer to the screen check equal to the advancement distance. This causes the image to come up a bit short of the edges. A further refinement would be to advance the odd value distance and 'touch the wall' before reversing direction. 

# License Information
This work was done as part of MIT xPRO Professional Certificate in Coding. The code above comes with the following license:

MIT License
