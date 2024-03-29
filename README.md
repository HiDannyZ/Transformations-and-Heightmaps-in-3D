[![Maintenance](https://img.shields.io/badge/Developer-Danny_Zhu-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![Maintenance](https://img.shields.io/badge/Microsoft_Visual_Studios-C++-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)

# Transformations-and-Heightmaps-in-3D

# Disclaimer!
There are executable and media files, so any interested people are able to run the application themselves. 
  
The Program was written in C++ utilizing:
- OpenGL
- Microsoft Visual Studios C++.
  
# Video
[![YoutubeImage](https://github.com/HiDannyZhu/Transformations-and-Heightmaps-in-3D/blob/master/YoutubeImage.png)](https://www.youtube.com/watch?v=Z9tJMM_5zTE "Everything Is AWESOME")

# Features

## SkyBox

The cubes are contained in a skybox: a cube with textures of ground,horizon, and sky that fit together to appear as a seamless large environment. To give my skybox a more realistic effect of being infinitely far away, I had it unaffected by the translation of the camera. Thus, no matter how far I moved, the skybox will never get closer.

## HeightMap

I rendered in a surface mesh to create a detailed terrain of mountains. It made the scene look less bland and more cool.


## Transformations of the cube

This was done through matrix manipulation of each cube's model matrix.


# How to Run the Program:
  Download the Project_1.rar
  
  KEEP ALL FILE NAMES THE SAME and the same order.
  
  Double-click Project1.exe. 

#  Preamble
Press T to get on the track and press again to get off track

Press the U,I,O to increase transformations

Press the J,K,L to decrease transformations

Shift+Key will alter scale

Control+Key will alter translation

Key along will alter rotation rate

Pressing Comma will increase transformation Step

Pressing Period will decrease transformation Step

Pressing G will reset transformations

# Source for SkyBox Texture
http://www.custommapmakers.org/skyboxes.php
