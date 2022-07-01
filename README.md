# Canstructor
| [Features](#features) | [Installing](#installing) | [How to use](#how-to-use) |
|---|---|---|
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
3. Extract the **.zip** file and run the **.blend** file.

## How to use

### Lattice Object
The object that the generator going to use to convert the base mesh to.

### Base Mesh
The mesh that the generator gonna use to generate the sculpture. Join multiple mesh if you need more than 3.

### Size X, Y, Z
The area that the base mesh have to be in to trigger the generator. Resize this so that the black border surround your base mesh.

### Build Mode
Enabling this change the rendering to individual layer depending on the current frame. Make sure to the **End Frame** to the value of **Size Z**

### Threshold
The maximum allowed distance between the lattice object and the base mesh, object farther than the threshold will be deleted.

### Offset X, Y
Control the offset of every other layers.

### Triangle Grid
Enabling this change the default square grid to a triangle grid.
