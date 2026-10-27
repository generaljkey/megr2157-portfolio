# A7 – [Topic]

## Objective
For assignment 7, the objective was to use the SolidWorks Simulation program to perform a Finite Element Analysis (FEA) on Assignment 5's bracket design. The bracket was analyzed with a load of 600 lbf. Mesh configuration was used to evaluate the accuracy of the results. The bracket will then be modified to improve its strength and stiffness. 

## Outer Loop 1: Original Bracket Design

1. Preprocessing
   A. Static Stress Analysis
   First, a static stress study was initialized in SolidWorks Simulation to find test values of my original bracket design. I then made sure the material was edited for Aluminum 6061.

![A07 Material Edit](A07%20Material%20Edit.png)

   B. Fixtures and Constraints

   For assigning fixtures, I made the upper U shape of the bracket to be fixed with the force being applied to the lower cylindrical part of the bracket.

   ![A07 Fixed Geometry](A07%20Fixed%20Geometry.png)

   C. Applied Loading

   A downward force of 600 lbf was applied to the cylindrical section of the bracket. The simulated force will act as a simulated strap pulling the cylindrical section of the bracket. This load was selected from Assignment 5. 

   D. Mesh Selection 

   A solid mesh was generated for the bracket. First, I used the regular mesh settings and ran a simulation to obtain a base value for Von Mises and Displacment. 

![A07 First FEA Von Mises](A07%20First%20FEA.png)
![A07 First FEA Disaplacement](A07%20First%20Fea%20Displacement.png)

For the second mesh, I used a slightly finer setting to try to alter the values for Von Mises and Displacement to see if they converge at the needed 7%.

![A07 Second FEA Von Mises](A07%20Third%20Von%20Mises.png)
![A07 Second FEA Displacement](A07%20Third%20Displacement.png)

Lastly, I used the maximum fine mesh setting slider to get further values. 

![A07 Third FEA Von Mises](A07%20Second%20Von%20Mises.png)
![A07 Third Displacement](A07%20Second%20Displacement.png)

2. Computation
   The static stress study calculated the Von Mises stress, resultant displacement, and deformation of the bracket under the applied load with fixed geometry and specific mesh settings.

3. Data Interpretation
   Simulation Results
   For mesh 1, a maximum Von Mises Stress, in MPA, was found to be 1,972, a maximum displacement, in mm, to be 30.72, and a safety factor of 0.14.
   For mesh 2, a maximum Von Mises Stress was found to be 1982.4, a maximum displacement of 30.85, and a safety factor of 0.139.
   For mesh 3, a maximum Von Mises Stress was found to be 2,289, a maximum displacement of 31.35, and a safety factor of 0.12.

   A. Safety Factor

   The material yield strength was 275.8 MPA. The safety factor was calculated using the following formula, SF = Yield Strength / Maximum Von Mises Stress.

   Since the safety factor was well below a value of 1, my bracket design simulated a predicted stress to be above the materials yield strength. I believe this is due to my bracket design being insufficient for the applied load leading to abnormally high stresses while running the mesh studies.

   B. Maximum Stress and Location

   The maximum Von Mises Stress for Mesh 2 was 1,982.4 MPa. This stress occurred at the connection between the Upper U-shaped design and the vertical rectangular section connecting the cylindrical strap holder to the upper bracket design.

   C. Maximum Displacement and Location

   The maximum resultant displacement for Mesh 2 was 30.85 mm. This displacement occurred at the free end of the cylindrical strap holder, which is where the bending force was very large.

4. Error Estimation and Mesh Validation

    I used three different mesh settings for the tests. When comparing Mesh 1 to Mesh 2 test values, the stress difference percentage was 0.53% while the displacement difference percentage was 0.42%. When comparing Mesh 2 to Mesh 3, the stress difference percentage was 15.47% while the displacement percentage was 1.62%

   The displacement convergence testing was within the 7% for the three tests but for the stress convergence testing, Mesh 1 to Mesh 2 convergence met the 7% difference while Mesh 2 to Mesh 3 did not meet the convergence percentage of 7%. I am not sure why the mesh's met the convergence percentage test from Mesh 1 to Mesh 2 but Mesh 2 to Mesh 3 did not. This must indicate that the maximum stress is mesh sensitive as a much finer mesh setting caused a large maximum stress in Mesh 3. I may have used a much larger fine mesh setting than I should have as I changed the mesh setting slider from slightly fine to the maximum fine setting possible.

   5. Design Optimization

  After reviewing the value results for the three tests, I have discovered multiple ways I could improve my design to meet this convergence percentage value. 
  A big redesign feature would have been to add fillets to the vertical support. Adding fillets would have greatly improved the maximum stress mainly to the cylindrical section as well as the rectangular portion connecting the upper bracket design to this cylindrical section. 
  Another redesign feature that would have helped with the maximum stress would have been to increase the vertical supports thickness. By increasing the supports thickness, the bending stiffness would be improved as well at decreasing the maximum displacement while these forces are being applied. 


## Reflection

   This assignment taught me the importance of Finite Element Analysis programs as they can reveal specific areas in a design that need improvement or where I can expect failure to happen first. Changing the mesh settings of a feature can affect the study values greatly as well. Going into this assignment, I thought mesh settings were not important as I have never learned about utilizing mesh's in 3D modeling before. After using these settings for this assignment, I discovered that mesh settings play a vital role in analysis of a design. In my design in particular, the displacement values were consistent throughout all mesh setting changes, but the stresses varied tremendously. Without using a mesh, I would not have been able to identify just how weak of a design for the vertical supports were. Going into the design for this bracket in Assignment 5, I knew this vertical support would carry most of the stresses as this section would be relatively thin and smaller compared to the rest of the design but after seeing the variation in the difference percentages, I see the importance of redesigning and utilizing programs like FEA to discover these weaknesses in designs. 

   In total, I spent about 3 hours on this assignment. 

   

