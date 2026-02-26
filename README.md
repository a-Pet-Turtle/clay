# Clay 3D Modeler
A powerful 3D modeler that uses a techinique called visual hull reconstruction. Clay features a keyframe animator, import/export of *.obj, a face editor, and several smoothing techniques. Think of an accidental wannabe Blender.  
  
### Getting Started
To get started, create an object by pressing the [+ New] button. 
Then add your textures (or draw them).
Finally, press the [> Build Selected] button.  
  
### Known Bugs
The **Catmull-Clark Crash** occurs when more than 2 layers of smoothing are applied to the scene. This is less of a bug, and more of a "hey, watch out." As of Clay v3.5, you can apply as many layers of Catmull-Clark as you want, but any more than 2 is guaranteed to be slow.  

## What is...

### Visual Hill Reconstruction
***Visual Hull Reconstruction*** is a way of making a shape based off of "*images.*" Clay treats every object as a cube. To build the object, Clay looks at the provided pictures and makes an assumption of what the resulting shape will be.  
  
### Voxels
***Voxels*** are the pixels of the 3D world. The screen you are viewing this on is made of pixels. Tiny, 2D pixels. A voxel is a 3D equivalent of a pixel. While a pixel stores an (x, y) and color value, a voxel holds an (x, y, z) and color value.  
  
### Catmull-Clark
The ***Catmull-Clark Smoothing*** techinique is a way of smoothing objects by creating new faces with old ones to make something look more natural. The more layers of Catmull-Clark, the smoother the object. However, with Clay, it is recommended to be under 4, or else it is too slow.  
  
### Other
An ***object*** is a 3D shape.  
A ***face*** is the flat surface of an object.  
The ***scene*** is the 3D canvas where the objects are.  
  
## Copying
This app was created by [a_Pet_Turtle](https://github.com/a-Pet-Turtle/). You may reproduce or copy parts of this program, as long as you give me credit.  
