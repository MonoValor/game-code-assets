NOTE: READ THE CODE AND CHANGE THE OBJECT NAMES TO THE ONES BEING USED IN THE GAME TO AVOID COMPLICATIONS 


1. Create a new C# script called "HoverSlideObject" and attach it to the object you want to slide into the scene.
2. Copy the code


This script uses IPointerEnterHandler and IPointerExitHandler interfaces to handle mouse hover events. It will move the object towards the 
target position when the mouse hovers over it and move it back to its initial position when the mouse is no longer hovering over it.

1. Set the target position and slide speed in the Inspector, adjusting the values as needed.
2. To make sure the Event System can detect the mouse hover events, you'll need to have a Collider 
(such as a BoxCollider or SphereCollider) attached to the object and have a Canvas Group component on the same GameObject or one of its parents.
3. If you don't have an Event System in your scene, create one by right-clicking in the Hierarchy, then selecting UI > Event System.
Now, when you run the scene and hover your mouse over the object, it should slide into the target position and slide back when the mouse is no longer hovering over it.

If you think I forgot something or need clarification ask me.
