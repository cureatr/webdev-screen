**Please implement, using Javascript, a browser-based game described by the rules below.**

### Game rules

The game board is a 2D grid, 50 by 50 cells. Each cell can be empty or populated.

The initial state of the grid should be random, with approximately 25% of cells populated.

At each turn of the game, the game board evolves according to the following rules:

* Any populated cell with fewer than two neighbors becomes empty.
* Any populated cell with two or three neighbors stays populated.
* Any populated cell with more than three neighbors becomes empty.
* Any empty cell with exactly three or six neighbors becomes populated.

_The state of the board changes only after the next state has been computed._

The game provides controls to start, reset, pause, and resume gameplay.

### Other requirements

* You are free to use a common framework, for example React, and helper libraries.
* The game should be implemented using HTML DOM (i.e. not canvas, images, webgl, etc).

### Submission

Please email back a link to your Github repository containing the implemented game.
Individual commits showing incremental progress should be present.
The README should include instructions for running the game in the local browser.
