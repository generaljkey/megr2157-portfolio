# A3 – [Topic]

## Objective

For assignment A03, the objective of this assignment was to calculate and design a beam design with an aluminum material in CAD modelling. The beam design is meant to be a circular cross section that is fixed on one side with a force applied on the opposite side. First, hand calculations will confirm dimensions that will be inputted into SolidWorks equations lists that will then be used for the FEA test to obtain a safety factor, stress value, and deflection confirmation. The maximum deflection allowed that was given in the assignment was 0.009 inches. 

## Analyze

For the parametric design, a range of values for Applied Load and Young's Modulus were given to choose from to then calculate further information needed for the beam design. For the Applied Load, I chose 400 lbf and for Young's Modulus, I chose a value of 9,000,000 psi. I chose these values because they both were in the middle of the given ranges for this assignment. 

![Hand Calculations for Beam Design](IMG_2740.JPG)

With my hand calculations, I chose a beam design diameter of 0.75 inches. My area came out to be 0.4418 inches squared. Then, using the Bar Tension Elongation equation, the length of my beam design came out to be 89.46 inches. 

## SolidWorks

![SolidWorks Equation List](A03%20Equations.png)
![Beam Design Dimensions](A03%20Length%20and%20Diameter.png)

With SolidWorks rounding my values for length and area to only 2 decimal places, my length stayed at 89.46 inches. This rounding might have affected my values with the FEA test later on. 

 ## FEA Test

![Material Edit](A03%20Material%20Edit.png)

For the material of Aluminum, I had to make a custom material with the following parameters.

- Elastic Modulus = 9,000,000 psi
- Poisson's Ratio = 0.33
- Mass Density = 0.0975 lb/in^3
- Yield Strength = 40,000 psi

![Setting Fixtures and Mesh](A03%20Setting%20Fixtures%20and%20Mesh.png)

## Communicate

