Billards V1.0

Billards 

This project consists of the following C source files:
- main.c
- movement_handling.c
- drawing.c
- collisions.c
- arraylist.c

And contains one third party single header file library
- stb_image.h - used to load textures

# Features:

# Installation:
(For manual installation)
Clone the repo

` git clone https://github.com/Ray1291/BinaryToolKit`

Navigate to the directory

` cd "YOUR_DIRECTORY"`

compile the program

` gcc main.c arraylist.c drawing.c movement_handling.c collisions.c -o a.out -lglut -lGLEW -lGL -lGLU -lm -g `

Run it

` ./run.out`

# Usage
Upon running the program, a window will pop up with the balls setup ready for play. Just click and drag on the cue ball to fire it off.
Most game parameters can be changed in the provided pool.h header file. 

# Contributing 
Feel free to submit issues or pull requests. Contributions to improve the code or add features are welcome!

# Future Feature Plans
- Adding text drawing support using gltext.h
- Creation of a CMAKE file for easier compliation
- Menu to easily change game parameters (number of balls, strength of cue, etc...)
- Game modes (8-ball, 9-ball, Straight Pool)
