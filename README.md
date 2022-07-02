# [Canstructor](https://youtu.be/pY3FghSjlXM)
| [Features](#features) | [Installing](#installing) | [How to use](#how-to-use) | [Inputs](#inputs) |
|---|---|---|---|

## Features

- Automaticlly generate sculpture from geometry.
- Customizable can size.
- Show the amount of cans require.
- Customizable texture.
- Customizable offset.
- Build mode.

## Installing
1. Make sure you have Blender 3.1+.
2. Download this repo.
3. Extract the **.zip** file and run the **.blend** file inside.

## How to use

1. Select your can in the [Lattice Object](#lattice-object-object) field.
2. Select the object(s) that you're going to convert in the [Base Mesh](#base-mesh-object)  field(s).
3. Move your object(s) so that it's in the area surrounded by the border, resize the area if needed.
4. Change the other values (other than [Build Mode](#build-mode-boolean)) to your liking.

### Using [Build Mode](#build-mode-boolean)

1. Make sure that the start frame is set to 1 and the end frame at the bottom playback bar is set to the current value of `Size Z`.
2. `Ctrl + F12` to render out the layer, or go up to the render tab and click **Render Animation**.
3. The render will be inside the `Canstruction` folder, inside the same directory as the **.blend** file. 

## Inputs

### Lattice Object (Object)
The object that the generator going to use to convert the base mesh to.

### Base Mesh (Object)
The mesh that the generator gonna use to generate the sculpture. Join multiple mesh if you need more than 3.

### Size X, Y, Z (Integer)
The area that the base mesh have to be in to trigger the generator. Resize this so that the black border surround your base mesh.

### Build Mode (Boolean)
Enabling this change the rendering to individual layer depending on the current frame. Make sure to the **End Frame** to the value of **Size Z**

### Threshold (Float)
The maximum allowed distance between the lattice object and the base mesh, object farther than the threshold will be deleted.

### Offset X, Y (Float)
Control the offset of every other layers.

### Triangle Grid (Boolean)
Enabling this change the default square grid to a triangle grid.
