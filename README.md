# SmartGlass

NOTE: This repo uses these repos as submodules
[GUI](https://github.com/Av3boy/SmartGlass-Interface)
[Handtracking](https://github.com/Av3boy/Hand-Tracking)

## Introduction

SmartGlass is a computer assisted visual aid.
You can browse the web, scan what you are seeing and analyze it.

One primary function of the scan function is to calculate mathematical equations.
You draw a box around the area of the equation and let the SmartGlass calculate it for you.

### Software

Using a multithreading solution we will be running C++ With OpenGL to render the interface on the smartglass.

Along side C++, we will run Python which will be used to figure out where our hands are going to be.
The hand data will be sent out to the main program which will also send the data to C++ to handle user key strokes.

### Hardware

Using the latest Rasperry Pi 4 will be the best choice for its relatively small size and its large amount of processing power.

Rasperry Pi has built in WIFI so possible internet connections are possible as well.
Rasperry Pi is OpenGL 3.2 compatible. It also has 4 GB RAM so all the programs can use the proscessing power needed.

Using a projecting method we will send the light out of a lcd display onto a reflective glass onto a prism that will scale the image and then onto a piece of glass.

This way we will be able to see our hands and our surroundings.

###

A hotkey for toggling the interface.
Generate a 3D keyboard to handle first version controls.

### Links & References

https://www.amazon.com/2inch-IPS-LCD-Display-Module/dp/B082GFTZQD
https://en.wikipedia.org/wiki/Raspberry_Pi
https://www.raspberrypi.org/blog/vc4-and-v3d-opengl-drivers-for-raspberry-pi-an-update/
