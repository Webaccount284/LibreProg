Hello! The ".pmp" is a Penguinmod project file. Go to "https://studio.penguinmod.com/editor.html?nohqpen" and click on File, then load this project. 
You can import any procedural texture by loading a new sprite from your computer and selecting any file that ends in ".pms"
To export a procedural texture you have made, make sure the name is "proc_exampletexture" then right click the sprite and choose the export button.

If you want to create a new procedural texture, you can use the file "proc_base.pms" as a base and then edit it.

Use "_Timer" instead of the inbuilt timer
Use the "Random Number from () to ()" custom block instead of the inbuilt "pick random"

Press Space to Pause/Continue
Press Left arrow key to step backwards into the previous frame
Press Right arrow key to step forwards into the next frame
Press Enter to record frames

Stepping backward does not work for textures whose data is generated based on data from previous frames (e.g water)

If pressing Left does not work, that is because you are on the first frame (frame index is 0 on the first frame).

Color values are from 0-255, including Alpha.