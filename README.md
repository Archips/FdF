# FdF 

![fdf-demo](https://github.com/Archips/FdF/blob/main/fdf_demo_hd.gif)

## Project Highlights

- **Objective:** This project involves creating a wireframe model representation of a 3D landscape using the MiniLibX graphical library.

- **Representation:** The project aims to visualize landscapes by connecting points (x, y, z) with line segments (edges) to create a 3D wireframe model.

- **Features:**
  - Render the model in isometric projection.
  - Read landscape coordinates from a .fdf file.
  - Use MiniLibX for window management and graphical elements.
  - Additional projection method (e.g. parallel).
  - Zoom in and out functionality.
  - Translation of the 3D model.
  - Rotation of the 3D model.
  - Chang the color of the map.

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine [macOs version](https://github.com/Archips/FdF_macOs) | [linux version](https://github.com/Archips/FdF_linux).  
2. Navigate to the project directory.
3. Compile the source files using the provided Makefile (`make bonus` for all features on macOS).
4. Run the program, specifying a .fdf file as input:
   `./fdf [map].fdf`
5. The program will display the 3D wireframe model of the landscape in a graphical window.
6. To close the window and exit the program, either press the "ESC" key or click the window's close button.

## Keys  

  - move         `[w s a d]`
  - altitude     `[< >]`
  - zoom         `[- +]`
  - rotation x   `[up / down arrow]`
  - rotation y   `[left / right arrow]`
  - rotation z   `[; '`
  - change view  `[space]`
  - change color `[c v]`
  - reset map    `[r]`
  - exit         `[esc]`

## Notes

  - You can change the window's size by adjusting `WIDTH` and `HEIGHT` in includes/fdf.h
  - The window's exit button is broken in the macOs version 

## Author

[Archibald Thirion](https://github.com/Archips)




