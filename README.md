# Game-of-Life
An Interactive version of Conway's Game of Life, in Processing.

The Game of Life is a simple cellular automata "zero player game" that evolves on its own based on surprisingly simple logic.  It was devised by the mathematician James Conway.  This version comes pre-populated with patterns that lead to interesting results.  It expands the game to include interactivity, allowing "players" to draw patterns of their own, and manipulate the game as it evolves.

To run the code, copy it into Processing Version 3 or later, and play.  To download the latest version of Processing: http://processing.org.

To interact with the "game":

- Type "p" to generate a pattern from among the many that have been discovered over the years.
- Type "l" to generate a pattern of random lines.
- Type "spacebar" to pause the animation. Type "spacebar" again to un-pause it.
- Type "r" to reset the stage to its initial state.
- Type "c" to clear the stage.
- Type a number ("0" - "9") to refresh the stage with a percentage of randomly seeded cells.  The result is a percentage of cells 10 times the typed number that start the animation alive ("0" = 0%, "3" = 30%, "9" = 90%).  Future commands will execute with this percentage of additional seeds, until "r" resets the stage. There are 0 random seeds initially.
- Type "t" to include the text area in the animation.  Type "t" again to bring it back.
- Draw with your mouse to toggle cell states.  The animation pauses while your mouse is pressed and resumes upon release.  Pause the animation ("spacebar") before drawing to enable multiple strokes.
- Type the "enter/return" key to step to the next generation of a paused animation.

The code was designed to be easy to modify and explore creative possibilities.

To see it and play with it in a website, go here:
http://brianmaniere.com/fun/the-game-of-life-creative-technologist.html

For more on the Game of Life, here's a good summary:
https://en.wikipedia.org/wiki/Conways_Game_of_Life
