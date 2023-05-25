First, the slide-out animation:

1. With your widget panel selected, open the Animation window (Window -> Animation -> Animation).

2. Click "Create" to create a new animation and save it as "SlideOut" or similar.

3. With the record button enabled in the Animation window, move the panel to its off-screen 
position. Unity will automatically create keyframes for the start and end positions.

Replace puzzle and puzzleController with references to your actual puzzle and PuzzleController 
objects, and replace IsSolved() with your actual method for checking if the puzzle is solved.

This code will cause the game widget to slide out of view when the puzzle is completed. Remember 
to replace "SlideOut" with the name of your slide-out animation state.

In order for this to work, you will need to call CompletePuzzle when the minigame is solved. I'll have
puzzle solved part attached to the end of the minigames scripts so beare
