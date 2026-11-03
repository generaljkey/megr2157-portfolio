# A8 – Gears

## Objective
  For A08, the main objective is to design, test the structural analysis, and 3D model a gearbox that can be assembled using fasteners. The structural analysis consists of the load on both the 0.125-inch diameter input shaft as well as the 0.250-inch diameter output shaft. A journal bearing evaluation using equations from the Machinery Handbook will also be conducted to find out sizing, pressure velocity, and thickness. The values found using hand calculations will then be used to select the parts from McMaster-Carr website which with then be used in a 3D modeling software to construct the designed gearbox. 

  The gearbox uses a 9-tooth input pinion and a 24-tooth output gear that produces a gear ratio of 24:9. The design called for an output torque of 1.25 in-lbf and an output rotational speef of 1100 RPM. 

## Assumptions

With this assignment, there are multiple assumptions. 

Appropriate strength of shafts using Machinery's Handbook.

The gear train is ideal.

The moment of radial force from the gear train is small enough to be ignored. 



## Calculations for Input and Output Shaft

![A08 Input Shaft Calculations](IMG_2992.JPG)

Using the formulas derived from the Machinery's Handbook, a Tau max input value of 1222.31 psi was found. 

![A08 Output Shaft Calculations](IMG_2993.JPG)

Using the same formulas derived from the Machinery's Handbook, a Tau max output value of 407.44 psi was found. Based on the values of the Tau input and output maxes, the current diameters are sufficient to continue the design. A torque value for the output shaft was found to be 0.46875 in-lbf. 


## Journal Bearings Calculations

For the length of the shafts, I decided to make an assumption of the shafts being 1 inch in length. By having both shafts of equal length, this will help create easy paths of sliding without colliding with the housing walls of the gear box. 

![A08 Journal Bearing Calculations](IMG_2994.JPG)

Using the derived equations from the Machinery's Handbook, the values for Force acting upon the gears, the two bearings, Pressure for both the input and output shafts, as well as the Surface Velocity. 

The force acting on thee the gears was found to be 2.660 in-lbf meaning that a Force of 1.330 in-lbf is acting on the bushings. 

The Pressure for the input was 42.56 psi while the pressure for the output was 21.28 psi. 

The surface velocity for the input was found to be 96.00 ft per min while the output velocity was found to be 72.00 ft per min. 

Using both the Pressure and Velocity, the product is a value that will be used to select a material for the bushings. The PV for the input came out to 405.88 psi-ft per min while the output value was 1532.2 psi-ft per min. Using the Bearing Material Limits table from page 2361 in the Machinery's Handbook, I chose to use a material of Lubricated Graphite. The load capacity for this material was 600 psi which well suits the calculated pressures for both the input and output values. A Surface Velocity value of 2500 ft per min also exceeds the needed values for both the input and output. Finally, a PV limit value of 150,000 psi-ft per min also exceeds the calculated values of both input and output values. This material exceeds all needed calculated criteria for this design. 


## Journal Bearings Thickness Calculations

Using the found values for the Journal Bearings, we can then use a free body diagram to calculate the needed thickness of the bearing. 

![A08 Journal Bearing Thickness](IMG_2995.JPG)

From these calculations, the thickness needed to be 0.00266 inches for both the input and output shafts. With this thickness, I will be selecting a thickness of 1/16 inch bearing as this measurement is widely available in most commercial uses. 
With this thickness, the dimension for the input diameter was 0.250 inches while the output diameter was 0.375 inches. With these dimensions, I chose to use McMaster-Carr 6391K131 for the Output Shaft Journal. For the Input Shaft Journal, I decided to use McMaster-Carr 6391K111. 

## Design Sketch

For the design sketch, I sketched the gears inside the housing as well as the outside of the housing looking onto the output shaft side of the housing. 

![A08 Design Sketch](IMG_2996.JPG)

## SolidWorks 3D Model

 For the 3D Model, I went into SolidWorks and created the parts needed to assemble the gearbox housing design. 
 
 First, I created the input and output shafts using the hand calculated dimensions from previous steps in the assignment. The diameter of the input shaft was calculated to be 0.250 inches, and the diameter of the output shaft was 0.375 inches. Both shafts' lengths are to be 1.00 inches. 

 ![A08 3D Model Input Shaft](A08%20Input%20Shaft.png)

Next, I created the housing for the gearbox. I created the housing with two dimensions to hold both a thickness for the housing of 0.125 inches and have a large enough cavity to hold the gear and pinion. The housing had a depth of 0.50 inches with a outer diameter around the gear to be 1.6883 inches and a cavity diameter of 1.1833 inches. For the pinion, the housing diameter was set to 1.0583 inches and the cavity needed to be 0.5583 inches. I then created 4 tapped holes that are meant for a #2-56 UNC bolt sizing for the cover to fasten onto. 

![A08 Gearbox Housing](A08%20Gearbox%20Housing.png)

For the Gearbox Housing Cover, I created a mold of the same housing outer diameters for the gear and pinion followed by the 4 fastener holes and made the thickness of the plate to be 0.125 inches. 

![A08 Gearbox Housing Cover](A08%20Gearbox%20Housing%20Cover.png)

Finally, I assembled all the parts I created in SolidWorks as well as the downloaded gear, pinion, and Journal Bearings. For the gear, I had to use a gear with 48 teeth since McMaster-Carr did not have a 9-tooth pinion. The gear chosen was part number 7880K24 and the pinion chosen has 18 teeth and the part number is 7880K19. The Journal Bearings chosen were part number 6391K111 and 6391K131. 

When assembling the gears and pinion, I had a clearance issue with the teeth that I could not figure out how to fix. I mated the gear and pinion to their appropriate shaft as well as the correct Journal Bearings to the correct shafts on both the covers and opposite side of the housing. Finally, I mated the cover onto the housing to cover the entire assembly. 

![A08 Final Assembly](A08%20Final%20Assembly.png)





