# A9 – Pulleys

## Objective
For this assignment, I was given parameters to design a pulley system that included the belt, shafts, journal bearings, and a frame design while being able to transfer rotational power while maintaining structural integrity and minimizing friction and wear.  The parameters given was two, 3-inch diameter pulleys, center distance of 5 inches, and operating at a selected rotational speed of 1,500 RPM. 

The design process involved selecting a polyurethane belt, calculating and selecting a diameter for the 1060 steel shaft, and selecting a suitable journal bearing material based on bearing pressure, surface velocity, and PV rating. 

The overall goal was to design a functional pulley system that meets the required the constraints while maintaining a Safety Factor of at least 3. 


## Belt Selection

To find the needed calculations for the belt selection, I drew a Free Body Diagram as well as listing the known and unknowns in this design problem. The belt material was given as polyurethane rubber with a yield strength of 471 Psi. Using the given Safety Factor of 3, the calculated tensile stress was found to be 157 Psi. 

Using the drawn Free Body Diagram, with an assumption of 6 lbf-in of transmitted torque, the tight side tension was calculated to be 7 lbf while the loose side tension was calculated for 3 lbf. The tight side tension was found using the minimum required cross-sectional area using the normal stress equation. 

The minimum cross-sectional area was calculated to be 0.04459 in^2. From this value, a diameter of the belt was found to be a needed value of 0.2383 inches. I selected a 1/4 inch diameter polyurethane belt as this exceeds the diameter minimum calculated. The tensile stress, with this new diameter, was then found to be 142.6 Psi which resulted in a safety factor of 3.30. 

The approximate belt length was found to be 19.425 inches.  

![A09 Belt Selection Calculations](A9%20Part%201.JPG)
![A09 Belt Selection Calculations](A9%20Part%201.1.JPG)


## Shaft Design

For the shaft design, I used the same process as the belt design with a free body diagram as well as listing the knowns and unknowns. I then used the torque and shear stress formulas to figure out the diameter of the shaft which came out to be 0.1174 inches. I then selected a diameter of 1/8 inch for readily available materials. The allowable shear stress was calculated to be 18,898 Psi and the maximum shear stress was found to be 15,644 Psi with a safety factor of 3.62. 

![A09 Shaft Diameter Calculations](A9%20Part%202.JPG)
![A09 Shaft Diameter Calculations](A9%20Part%202.1.JPG)


## Journal Bearing 

The journal bearing that I had to use had to have a RC5 fit with a hole +0.7 thousandths of an inch. With a pressure value of 159.11 Psi, Velocity value of 49.09 ft per min, and a PV value of 7,810 psi-ft per min, I decided, from the material properties in the Machinery's Handbook on page 2440, to use the Porous Bronze. This material well exceeds the allowable values needed for the calculated values based on my design. 

![A09 Journal Bearing Calculations](A9%20Part%203.JPG)
![A09 Journal Bearing Calculations](A9%20Part%203.1.JPG)


## Frame Design

For the Frame Design of the pulley system, I decided to use a rectangular base with 4 column posts to hold the pulley system together. I believe this rectangular design base will keep the pulley system together while not allowing movement while the pulley system is in motion. With a material of 6061-T6 Aluminum due to its high strength and lightweight properties, this base will hold this pulley system sufficiently 

![A09 Frame Design](A9%20Part%204.JPG)


## Lesson's Learned 

Throughout this assignment, I learned more about pulley systems. Being already passing Solid Dynamics, I had worked on similar problems in finding tension values as well as minimum diameter of belts or shafts for an applied torque so, I felt comfortable solving and figuring out the needed formulas to find these values. With this assignment, I further understand the importance of hand calculations when designing components. These values need to be compared as well as imagined to fully understand what the actual design problem is and how the overall shape will be in a 3D format. As I complete these assignments, I further am improving my problem solving and design skills with given parameters and a problem statement. 

Total time spent: 5 hours. 



