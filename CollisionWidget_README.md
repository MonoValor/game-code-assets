*NOTE USE THIS WHILE ALSO USING WIDGETANIMATION AT THE SAME TIME TO AVOID CONFUSION LATER*

1. Make a new UI Panel in your scene (right click in hierarchy -> UI -> Panel), which will serve as the pop-up widget. 
Set it as inactive from the Inspector.

2. Add the code to a new script on your player character (assuming you have a tag "Enemy" on your enemy object to make things easier and if
you're not using tags what are you doing!).

The gameWidget variable should be set to your UI Panel in the Unity inspector. 

3. Now, when your player character collides with any 
GameObject tagged as "Enemy", the game widget will be made active, making it pop.

4. Remember, for the collision to work, both the player and the enemy need to have Collider components and at least one of them needs to 
have a Rigidbody component. Also, 

If you forget to tag your enemy objects with the "Enemy" tag or something simmilar I'll find you.

You can customize your UI Panel as you want, adding buttons, texts, images, etc. You can also add more complex behaviors, 
like disabling player control when the widget pops up, or adding a button on the widget to close it.
The animation for the widget is in WidgetAnimation.
