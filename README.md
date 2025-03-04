## Project YARA - Hardware
<p align="center">
 <img src="https://github.com/aSrki/YARA-Hardware/blob/main/images/YARA.png?raw=true" width="200"/> <img src="https://github.com/aSrki/YARA-Hardware/blob/main/images/RobotAssembly.png?raw=true" width="350" />
</p>

The idea of YARA hardware is for it to be easily changable and possible to build it at home as a DIY project. 
I tried to make as many parts 3D printable as possible, and anyone who tries to do it themselves should need to buy only a few things. 
Even though i added bearing in images of certain assemblies, they are not included in .STEP model of a robot beacuse you should change
them to once available to you in your region. The same idea applies to NEMA stepper motors, and if you have some other NEMA17 you should be able to just plug it in in joints 1-3.
The 4th and 5th joints need to have smaller NEMA motors bacause of the relativelly small form factor of the robot.

Here I will show two main assemblies that where designed in such a way for 3D printing and cost savings. Are they perfect? Well no... but they are good enough keeping in mind that they are basically free.

# First joint assembly
<p align="center">
 <img src="https://github.com/aSrki/YARA-Hardware/blob/main/images/FirstJointSimplified.png?raw=true" width="400"/>
</p>

First joint assembly is designed using 3D printer rollers as an axial bearing. It is certainly not a perfect solution, but it works well and it is a lot cheaper and a lot more accessible than buying an axial bearing. Two large ball bearings are used to reduce radial forces to a minimum. Electronics are in the base of the robot, and are further descibed in firmware submodule.


# Cycloidal reductor assembly
<p align="center">
 <img src="https://github.com/aSrki/YARA-Hardware/blob/main/images/CycloidalDrive.png?raw=true" width="600"/>
</p>

Cycloidal reductor was chosen because of its small size and relatively large reduction radtio. It is easy to 3d print and it works well enough. Reductor, as well as robot, was drawn in OnShape. Reductor was designed using `Cycloidal drive` extension, and it was possible to print it without need to change any of the dimensions.
