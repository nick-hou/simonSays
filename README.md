# simonSays

## A simple memory game I built during bootcamp.

### The Game

Hosted in (github pages)[https://nick-hou.github.io/simonSays/]

To play the game, press any key to start. On each level N, the button that flashes is the Nth color in the sequence. At each level, you will need to click through the entire sequence.

Example - level 1, blue flashes. Click blue. Level 2, red flashes. Click blue, then red.

### The Code

All the logic is written in game.js, which uses jQuery to set listeners, animate buttons, and update headings. The button sequence, as well as the user inputs for each level, are stored in arrays and compared after each click. If the click was correct, move on or advance the level. If not, restart the game.
