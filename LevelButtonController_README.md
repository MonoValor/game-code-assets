To create clickable level buttons with hover effects and cutscene transitions, you can 
use Unity's UI system and a simple script. Here's a step-by-step guide:

    1. Create a new C# script called "LevelButtonController" and open it.
    2. Inside the script, add the code

This script listens for button clicks and loads the specified cutscene scene. It also saves the 
index of the level scene to be loaded after the cutscene.
   
   1. In your Unity project, create a new UI Canvas (right-click in the Hierarchy, UI > Canvas) 
   if you don't have one already.
   2. Right-click on the Canvas, and create three UI Buttons (UI > Button) for levels 1, 2, and 
   3. Attach the "LevelButtonController" script to each button.
   4. For each button, in the Inspector, assign the Button component to the levelButton property, set the 
    cutsceneSceneIndex to the build index of the respective cutscene scene, and set the levelSceneIndex to 
    the build index of the respective level scene.
   5. Update the button text to show the level number (e.g., "Level 1", "Level 2", "Level 3").
   
Continue to HighlightedColor_README for the directs to have the buttons slightly glow and clicking the said button 
will show a brief cutscene before bringing you to that level.
