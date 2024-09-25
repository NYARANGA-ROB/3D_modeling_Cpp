# Model Builder - CS 663 Project 1 #
Overview

This project implements a basic 3D model builder that can:

Load and display a 3D mesh from a .ply file.

Create and animate a custom 3D character using OpenGL primitives.

Allow user interactions such as toggling between the loaded mesh and the custom 3D character, using sliders for animation controls, and more.

# Project Structure #
 main.cpp: Contains the main function to run the program. It includes the initialization of the GUI, OpenGL settings, and the event loop to handle user inputs.


tgaClass.cpp and tgaClass.h: Implements the TGA image loading functionalities, used for texture mapping in the OpenGL environment.

model_loader.cpp (to be created): Contains the implementation of the plyload() function for reading a 3D mesh from a .ply file.

model.h (to be created): Holds the data structures for storing vertices, edges, and triangles from the mesh.
# Features #
Mesh Loading (Part 1)
Load Mesh Button: Click this button to load a .ply file and visualize the mesh in the OpenGL window.

Mesh Rendering: The loaded mesh will be displayed as a set of triangles.

Toggle ('t' key): Press the 't' key to toggle between the loaded mesh and the 3D model created using OpenGL primitives.

# Hierarchical 3D Modeling (Part 2) #
3D Character: A custom 3D character composed of at least 10 primitives with 4 levels of hierarchy.

Animation Controls: Sliders allow the user to manipulate specific joints of the character, and a pre-defined animation sequence can be toggled on or off.

Dynamic Controls: Some sliders will affect multiple joints simultaneously to create realistic character movements.

# Installation Instructions #
   Prerequisites
Visual Studio 2022 (or later)
FLTK library (pre-installed in the provided skeleton code)

OpenGL and GLU libraries

Windows OS (recommended)

# Build Instructions
Open the Project: Navigate to the project folder and open the .sln file using Visual Studio 2022.

Build the Solution: In Visual Studio, click Build -> Build Solution. Ensure that there are no compilation errors.

Run the Application: Once the build is successful, run the project. The OpenGL window and user interface should appear.
# Usage
Loading a Mesh:

Click on the Load Mesh button in the UI.
Select a .ply file to load a 3D mesh.

The mesh will be rendered in the OpenGL window.
Animating the 3D Character:

Press the 't' key to toggle between the loaded mesh and the 3D character.

Use the sliders to manipulate the character's joints.
To view the pre-defined animation, enable the animation option from the menu.


 
