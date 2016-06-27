# Game-of-Life
An Interactive version of Conway's Game of Life, in Processing.

The Game of Life is a simple cellular automaton "zero player game" that once set up evolves naturally based on its own simple logic.  It was devised by the mathematician James Conway.  This version comes pre-populated with many of the patterns that have been discovered lead to interesting results.  It also expands the game to include interactivity, allowing "players" to draw patterns of their own, and manipulate the game as it evolves.

For more on the Game of Life, Wikipedia provides a good summary:

https://en.wikipedia.org/wiki/Conways_Game_of_Life

To run the code, copy it into Processing Version 3 or later, and play.  To download the latest version of Processing: http://processing.org.

To interact with the "game":

- Type "p" to generate a pattern from among the many that have been discovered over the years.
- Type "l" to generate a pattern of random lines.
- Type "spacebar" to pause the animation. Type "spacebar" again to un-pause it.
- Type "r" to reset the stage to its initial state.
- Type "c" to clear the stage.
- Type a number ("0" - "9") to refresh the stage with a percentage of randomly seeded cells.  The result is a percentage of cells 10 times the typed number that start the animation alive (0 = 0%, 3 = 30%).  Future commands execute with these additional random seeds until: type "r" to reset the stage.
- Type "t" to include the text area in the animation.  Type "t" again to reset it.
- Draw with your mouse to toggle the cell states.  The animation pauses while your mouse is depressed and resumes upon release.  Pause the animation using "spacebar" first to draw more than once.

The code was designed to be easy to modify and explore creative possibilities.
