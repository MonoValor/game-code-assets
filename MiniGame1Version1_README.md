This is a little tricky to follow as this uses multiple scripts with default names to work with so ask me if you have any questions:

1. Create a Circle prefab with a Collider (e.g., a BoxCollider2D or CircleCollider2D). 
Then, create a script Circle.cs and attach it to the Circle prefab. The script is called CircleMouse

2. Next, create a new script, MiniGameController.cs, and attach it to your game widget. The script for this is called MiniGameController

3. The Circle Mouse script should have a minigamecontroller call inside of it

4.This code will spawn a new circle every second within the boundaries of the widget (assuming the widget's center is at (0,0) and its 
size is (2,2)). When a circle is clicked, it will notify the MiniGameController, which will increment its counter. If enough circles 
have been clicked, you can then handle winning the game .
