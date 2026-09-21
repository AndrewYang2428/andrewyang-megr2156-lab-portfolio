# A5 – Lab #5: Design a Snap Fit

## Modeling:

Model each of the components. Research a common Young's Modulus and yield strength of PLA. Use a Safety factor of 3.5. Choose a transverse load between .25 lbf - 5 lbf. The dimensions will depend on the flexing using the chosen load. The axial load of the clip should be in between 5 lbf - 10 lbf.

Initially chose the width and base of the flexure.

Solve  the length of the flexure using the beam equation for cantilever beam with a concentrated load at the free end.

Generate a separate FBD of each component.

Make sure the stress is less than the strength of material and SF.
- Determine the bending stress of the flexure component using appropriate force. Make sure the stress is less than the strength of material and SF.
- Determine the axial stress of the flexure with an appropriate load.
- Determine the average shear stress of the flexure protrusion.
- Iterate if needed.

## Parametrically design:

Use parametric design where appropriate.

Digitally sketch in CAD your design using the dimensions design in the first step.

In your documentation answer the following questions and/or apply the statements to your work.
- What are the parameters used?
- Why did you choose the specific parameters?
- What values did you choose for the specific parameters?
- Did the values change throughout the process? If so, why?
- Take many pictures of the different stages of the CAD model.
- Detail the decision making process and how you determined the engineered allowances of the interactive parts.
- Take a picture of the overall design in CAD.

Material: PETG
Elastic Modulus: 2000 MPa = 290075.48 psi
Yield Strength: 50MPA = 7251.9 psi
Safety Factor: 3.5
Transverse Load: 1lbf
Axial Load: 5lbf
Width: 0.1 in
Thickness: 0.15 in
Length: 0.9993 in

For my Snap feature, I designed a rough prototype of a buckle or clip that you will see on backpacks and lunchboxes. I created a sketch to get the overall shape of the design and then when I calculated for the length, I completed my design and made specific changes to fit the idea of what I wanted. For this process, there were many trial and errors to get the best fit for the clip. I had to make slight changes throughout the process to make sure that it would fit and clip on correctly. There are two components to this design so when there are changes being made to one component, you have to make sure that the other component will compliment that change. This design required a lot of balancing between the two components. 

## 3D printing  and Test:
### Research:

Find one source that discusses how build orientation affects the strength of an FDM printed part. Based on what you find, does your chosen orientation for the flexure line up with what the research recommends for a part under bending load? Explain your answer in a short paragraph in your Research section.



Show the 3D printing process including the pre-process. Some, not all questions, to answer are outlined below to guide your documentation.

- Outline reasons for the pre-processor layout.
- Change the support default to organic, paint on support, or snug.
- Reason why you chose one of the support systems.
- Outline reasons for build orientation.
- Outline slicer settings and reasons for the settings.
- If you use supports, outline the reasons.
- Detail any mistakes throughout the process.
- Detailed lessoned learned throughout the process, the more detail the better
- Resources and actual time it took from start to finish

When printing this design, I had to use supports for the second component because it was hollow. To have a smooth print process, I had to use supports on the inside to keep the wall from collapsing in. I decided to use the grid support instead of using the organic or the snug support because I wanted to easily get the supports out without damaging the walls of the cover component. Since this was my first time using supports on a design, I had to figure out how to use the support tool on PrusasSlicer. It was very simple to figure it out, but when I printed out my first part, I didn't add enough supports to hold the top wall, so it caved in after a couple runs. The Clip didn't slide in smoothly either so I had to make some changes to the slot as well to make sure that they fit correctly. 




