This gives you the ability to and drop the pipes from the inventory grid to the actual level.

1. Create a new C# script called "DragAndDropObject" and attach it to the object you want to drag and drop.
2. Copy the code

This script allows you to drag the object and snap it to the grid when released. That was it'll be easier to position them on the level

1. In the Unity Inspector, adjust the grid Size property as needed to fix the level and inventory
2. Make sure that the object you want to drag and drop has a mesh (such as a Cube or Sphere) and a renderer component (such as a Mesh Renderer)
for proper visibility. Also, ensure the object has a collider (such as a Box Collider or Sphere Collider) to detect mouse input.
3. For improved performance, create a new layer called "Ignore Raycast" in the Layer dropdown menu (Edit > Project Settings > Tags and Layers) 
and assign it to the objects you want to exclude from the raycast. (Google told me this is a good thing, idk why)
4. Run the scene, you can drag and drop the object from one grid to another, and the object will snap to the grid when released.
