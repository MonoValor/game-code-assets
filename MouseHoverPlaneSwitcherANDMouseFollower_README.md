To have the ability to switch between different planes when the mouse hovers over a specific area and switch
back to the first plane when the mouse hovers over the same area again, I thought using a trigger collider and a script would 
be the best bet. 

-This is the for Plane switcher
1. Create a new C# script called "MouseHoverPlaneSwitcher" and attach it to an empty GameObject in your scene.
2. add the code

-This is for the Mouse Follower
1. In the Unity Inspector, assign the planes array with your plane GameObjects.
2. Make sure that each plane GameObject has a mesh (such as a Plane or Quad) and 
a renderer component (such as a Mesh Renderer) for proper visibility.
3. Add a Box Collider or Sphere Collider to the same GameObject where the 
"MouseHoverPlaneSwitcher" script is attached, and set the Collider's "Is Trigger" 
property to true.
4. Create a small GameObject representing the mouse cursor, such as a small sphere
or cube, and give it a unique tag like "MouseCursor".
5. Attach the following "MouseFollower" script to the mouse object

Now, when you run the scene and hover the mouse cursor over the trigger area, the script will switch between the 
different planes in the order you've set in the Inspector. When you hover over the same area again, it will switch 
back to the first plane.

If you think I forgot something or need clarification ask me.
