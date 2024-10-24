# Minecraft Clone - Basic Version (OpenGL C)

## Project Overview

This project is a **basic version of Minecraft** developed using **OpenGL in C** as part of the 3rd Semester Computer Graphics course. The goal of the project is to demonstrate the use of **OpenGL** for 3D rendering, user interaction, and basic terrain generation in a voxel-based world. It focuses on the fundamental graphics principles like 3D object manipulation, rendering, lighting, and camera controls.

## Features

- **Voxel-based World**: The world is built from cubes (voxels) that can be placed and removed.
- **First-Person Camera**: Navigate the world using a first-person perspective, allowing the player to explore and interact with the environment.
- **Basic Block Types**: Includes block types such as dirt, grass, and stone for basic interaction.
- **Terrain Generation**: A simple algorithm is used to generate a flat or randomized terrain.
- **Block Placement and Removal**: Players can place and destroy blocks within the world.
- **Basic Lighting**: Simple lighting and shading techniques are used to create more realistic visuals.
- **Player Movement**:
  - **`W`**: Move forward
  - **`A`**: Move left
  - **`S`**: Move backward
  - **`D`**: Move right
  - **Space**: Jump
  - **Mouse**: Look around

## Installation and Setup

### Prerequisites

Make sure you have the following installed:
- GCC or any other C compiler
- OpenGL and GLUT libraries (for rendering and window handling)
  
For Ubuntu/Debian-based systems, you can install OpenGL and GLUT with:
```bash
sudo apt-get update
sudo apt-get install freeglut3 freeglut3-dev
sudo apt-get install binutils-gold gcc make libglew-dev mesa-common-dev build-essential libgl1-mesa-dev libglu1-mesa-dev
