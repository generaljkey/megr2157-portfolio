# A2 – Truss Stress Analysis

## Objective
 For this assignment, I was tasked with designing and 3d modeling on a software for a planar truss with A500 structural steel as the material. 

 ![Figure #1 from assignment description](Figure#1.png)

The dimensions and load for the given diagram were P=25kN, a=0.4 m, b=0.3 m, Point A is a pin, and Point B is a roller. 


## Decide

I decided to choose a 7-member truss design because of the simplicity of the design for hand calculations with simple geometry and I have seen many trusses designs similar to this design from buildings or large ceiling supports. 

## Analyze

The first step in this assignment was to start with the hand calculations for all the joints using Static's. I started with finding the forces for the support points A and B. Using static equilibrium in both the y and x axis's as well as using the static moment equilibrium, I was able to then find these values were necessary in further calculations for each joint at C, D, and E. Below are the calculations for each joint with free body diagrams, symbolic and numerical equations and their values. 

![Part 2a i, ii, iii, and iv](IMG_2715.JPG)
![Part 2a i, ii, iii, and iv](IMG_2716.JPG)
![Part 2a i, ii, iii, and iv](IMG_2717.JPG)

After finding all of the forces for each joint, I then used the largest internal force to calculate the minimum area needed through my hand calculations that will handle the found materials yield strength of 317 MPa, a safety factor of 3.5, and density of 7850 kg/m^3. 

![Part 2b i, ii, iii, and iv](IMG_2718.JPG)

Lastly, I used equations I learned from Solid Mechanics class to find the cross-sectional area of the 5 pins needed for my 7-member truss design using shear stress equations. The given values for the hardened tool steel for these pins were a yield shear strength of 170 ksi and a density of 0.278 ln/in^3 with a safety factor of 4. I had forgotten the process of finding pin diameters and pin area so, I utilized YouTube as well as my Solid Mechanics notebook to find help videos and examples on the process to solve. 

![Part 3a i, ii, iii, iv, and v](IMG_2719.JPG)

## SolidWorks Modeling 

For software, I chose to use SolidWorks. A friend of mine recommended SolidWorks as he mentioned it was comprehension able for beginners and the software listed for this assignment were not familiar to me. 

First, I built the truss design, extruded the truss to my calculated dimensions of 15mm by 15mm, then cut holes for the pins at each joint. 


