# Minicraft clone (for now)

Currently has a working gameloop which produces a window as well as the ability to render to it.

Want to make it have a tilemap with 216 uniquie colors, on a 256x144 display

When sprites are added they are created in grayscale and then are assigned 4 colors each at runtime so one sprite can be re-used for multiple tiles.

Depending on how the color is used in the code, each of the 4 colors is defined by 3 rgb digits, and each sprite is made up of 4 of these colors.

- [] Create basic tilemap
- [] Set up 216-color palette 
- [] Add user input to basic object
- [] Add sprites