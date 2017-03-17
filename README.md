# Ocean Surface

Authors: Jiashuo Li, Xie He, Ting Gong

This is a real-time ocean surface simulation and rendering program. The ocean waves are simulated using a statistical model based on oceanographical research, and are rendered using OpenGL Shading Language (GLSL). This is a course project for Fall 2015 CSCI-580 "3D Graphics and Rendering" at USC.

This program was written in C++ and GLSL.

This program was developed using Visual Studio. You should use Visual Studio if you want to compile it.

Our OpenGL framework is based on [Learn OpenGL](http://www.learnopengl.com/). And the following libraries are used in this program:
* `GLFW` for window management;
* `GLEW` for GLSL;
* `FFTW` for Fast Fourier Transform (FFT) in statistical ocean wave modeling;
* `SOIL` for screen capturing;
* `FFmpeg` for converting screenshots to video.

You can see our [project report](https://github.com/Shane-Xie-He/OceanSurface/raw/master/OceanSurface.pdf) for detailed explanation of the algorithms of our project.

The ocean wave simulation algorithm we referred to is also described in [*Simulating Ocean Water*](http://graphics.ucsd.edu/courses/rendering/2005/jdewall/tessendorf.pdf).

## Result

We made two videos for [a wavy surface](https://youtu.be/U2fkrXxvPRY) and [a calm surface](https://youtu.be/ewAPFoVxfFE) with N = M = 1024.

Here are some screenshots:

![](https://github.com/Shane-Xie-He/OceanSurface/raw/master/screenshots/screenshot1.jpg)

![](https://github.com/Shane-Xie-He/OceanSurface/raw/master/screenshots/screenshot2.jpg)

![](https://github.com/Shane-Xie-He/OceanSurface/raw/master/screenshots/screenshot3.jpg)
