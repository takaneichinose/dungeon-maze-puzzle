# CSS Only Retro Dungeon Maze Puzzle

## Description

This is a simple maze or dungeon escape game, with its functionality made entirely in CSS.

The main goal of this game is to of course find the finish line.

The main rule of this game is to click the horizontal or vertical tile beside the character. You may not click diagonally.

My tips for you in playing this game; Move slowly, you might get the key without noticing.

## Instructions

This setup is designed to be editable, and to become something like a game engine. As of now, there are only few types of tile may be inserted into the game map. Those are the below, and its usage.

- S -> The starting point.
- F -> Escape door.
- K -> Key to open the locked door.
- L -> Locked door. How to input: L_x-y where x is the x index (of array)
  of K, and y is the y index. Array is declared as 2 dimensional array.
- W -> Wall. You can't pass here.
- T -> Tree. You can't pass here.
- B -> Barrel. You can't pass here.
- M -> Monster. Don't go here, you'll lose.
- space -> Tile where you can walk.

I made the images using Aseprite. I've been practicing a lot in creating an 8-bit or pixel art image for a game.

## Resources

[Aseprite](https://www.aseprite.org)

[Creepster Font](https://fonts.google.com/specimen/Creepster)

## Building the program

For my future reference, below is the way in how to build the program.

1. Clone the repository
2. Optional: Install [yarn](https://yarnpkg.com/) as package manager
3. Install the dependencies using yarn ``` # yarn ``` or using npm ``` # npm install ```
4. Build the main program using yarn ``` # yarn build ``` or using npm ``` # npm run build ```
5. At the step above, the distributed program will be produced, and _dist_ folder will be generated. The step from here will be optional if you want to run the program on the localhost.
6. Create a local virtual server using yarn ``` # yarn start ``` or using npm ``` # npm start ```.
7. After building, usually it can accessed at [http://localhost:1234/](http://localhost:1234/).
