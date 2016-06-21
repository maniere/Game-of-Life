# Game-of-Life
An Interactive version of Conway's Game of Life, in Processing.

The Game of Life is a simple cellular automaton "zero player game" that once set up evolves naturally based on its own simple logic.  It was devised by the mathematician James Conway.  This version comes pre-populated with many of the various patterns that have been discovered lead to interesting results.  It also expands the game to include interactivity, allowing "players" to draw patterns of their own, and manipulate the game in real time as it evolves.

For more on the Game of Life, Wikipedia provides a good summary:

https://en.wikipedia.org/wiki/Conways_Game_of_Life

To run the code, copy it into Processing Version 3 or later, and run it there.  You can download the latest version of Processing here: http://processing.org.

To interact with version 1 of the "game" you may do the following:

Type "p" to generate a new random pattern from among the many classic patterns that have been discovered over the years.
Type "l" to generate a new pattern of random lines.
Type "c" to clear the screen and pause the animation so you can draw with your mouse to create your own patterns.
Type "spacebar" to un-pause the animation when it's paused, or to pause it when it's running.
Type "r" to reset the entire stage with a new pattern and text.
Type any other key to activate the text so that its cells participate in the algorithm.
You may at any point draw with your mouse to toggle the cell states.  Due to the high frame rate of the animation how you are affecting the algorithm will not be obvious.  It is however easy and obvious to draw with your mouse when the animation is paused.

To interact with version 1a of the "game" you may do the following:

Type "p" to generate a new random pattern from among the many classic patterns that have been discovered over the years.
Type "l" to generate a new pattern of random lines.
Type "c" to clear the screen.  Useful in combination with spacebar to clear the stage and pause the algorithm for drawing (see below).
Type "spacebar" pause animation, or to un-pause it if the algorithm has already been paused.
Type "r" to reset the entire stage with a new pattern and text.
Type the numeric keys (0 - 9) to refresh the stage with a the percentage of cells that are randomly seeded corresponding to 10% * the numeric value. (e.g., 0 = 0%, 3 = 30%).  This random_seed value persists until you type another numberic value to change it or "r" to reset the stage.
Type any other key to activate the text so that its cells participate in the algorithm.
You may at any point draw with your mouse to toggle the cell states.  The animation pauses while your mouse is clicked.  If you want to draw something complicated it is easiest to pause the animation using the "spacebar" first.

There are many more updates to come, including a simpler version for class.  Ok, the simpler version is not ready for class.  But Don't worry, I'll post it, and I'll help make it easy to understand!
