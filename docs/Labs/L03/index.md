# A3 – Lab#3: Design Something Small

## Design:

Document the design process, which includes many pictures with an overview of images at the different stages.

Detail the steps and reasons/decisions from start to finish.

For this project, the requirements were:

  - Design a small object on a parametric CAD system.
  - No more than 0.5in. tall
  - No overhangs
  - Large enough to use in-fill
  - Modify wall thickness
  - No more than 1.5in by 1.5in
  - Print time < 1.5 hours

My design for this project is a cable holder to help with organization of all of the cables I have hanging behind and under my desk. My intentions when designing something is for it to be functional and to help solve a present problem. I chose this design because this was a small design that I could use to represent in-fill, different in-fill patterns, and wall thickness.

<p align='center'>
<img width="736" height="607" alt="Small_Design_Dimensions" src="https://github.com/user-attachments/assets/a8fffb8c-cc7a-465b-af54-7f4bda31d01a" />
</p>

In this picture, it shows the dimensions of my cord holder. The overall size of the design is in between 1.5in(length) * 1.5in(width). I designed it to have a slot where I can put the cord through into the slot. The opening to it is slightly smaller to where the cords won't be able to come back out but it is still wide enough to take the cord holder off if I needed to. 

<p align='center'>
<img width="715" height="570" alt="Small_Design_Thickness" src="https://github.com/user-attachments/assets/58d9a49c-5a59-49f0-b419-8fc2e87d82d5" />
</p>

In this picture, it shows the thickness of the design. The requirements were that it was no more than 0.5in tall or thick so I made it to where it extruded out around 0.5in. 

<p align='center'>
<img width="757" height="547" alt="Small_Design_FinalLook" src="https://github.com/user-attachments/assets/0361f0b0-0a99-410a-bc5b-c0614237a679" />
</p>

This is the final design of my project. The final touches that I included were the roundness of the edges to give it smooth look, since the other side was already round. Overall, it is a small simple design that will help me with the organization of my desk. There are some adjustments that can be made to the hole and the slot of the cord holder, but it does work for what I designed it for. 

## Research:

Research three infills not shown in class to describe the geometry and why each in-fill is used.

Directly answer: how does infill percentage affect mechanical properties, and how do different infill patterns affect mechanical properties? Why use different wall thickness?

Some of the in-fills that were available in PrusasSlicer are Grid, Honeycomb, Triangles, Rectilinear, etc... There are many other in-fills that are available to us in PrusasSlicer but since this was a small design project, me and my partner Andy chose to go with the Triangles in-fill. We chose this in-fill because we thought the Triangle in-fill would have a stronger structural support for our designs. We also thought that the Triangle pattern would be a unique design to use for this in-fill. The three in-fill patterns that I chose was the Honeycomb, Triangles, and the Grid pattern. The Honeycomb in-fill is made of repeating hexagonal cells, similar to a bee honeycomb. The Honeycomb infill provides a good balance between strength and weight. It is also commonly used when a lightweight but relatively strong structure is desired. The Triangle in-fill consist of lines that intersect to form repeating triangular shapes throughout the interior of the part. This in-fill is useful when high stiffness and resistance to deformation are important. The geometry provides multiple load paths allowing forces to be distributed throughout the part. The Grid in-fill provides a good combination of strength, print speed, and material efficiency. The Grid in-fill is a pretty common in-fill pattern that is used. 


## Resources:

Website: https://pmc.ncbi.nlm.nih.gov/articles/PMC9865300/?utm_source=chatgpt.com

## Preprocessor/Printing:

Document the slicer information on PrusaSlicer. Some, not all, questions to answer are outlined below to guide your documentation.

Why choose the build orientation?

Did you need to scale? If so, why and how?

What different infill was used in your print versus the default, and why was it used?

What was the wall thickness modified to, and why? Directly answer: why use different wall thicknesses?

Detail any mistakes throughout the process.

I chose to lay my cable holder on the side to make the printing process easier because my design has a curve top surface. By orienting my design this way, I am able to get the shape that I want without having to worry about any supports or overhangs when printing. When choosing the in-fill pattern, I wanted to choose something that would help with the function of my design, which is to be flexible but sturdy enough to hold its shape. I joined my teammate Andy to print our designs together, so we chose the triangle in-fill pattern. 

I did have to scale my cable holder down a bit to fit the dimensions that we were required to meet. In PrusasSlicer, we are able to scale the model down and fix the orientation of the print to what we wanted. 

For my model I did not modify the wall thickness because I didn't want my print to come out too thick and stiff. The end-goal of my design was to be sturdy but also flexible so since I printed my design with my partner, we came to an agreement to print with the same in-fill pattern, in-fill percentage, and wall thickness.

## Print:

3D print your design using one of the FDM printers from the UNCC print farm.

Upload a video showing the 3D operation of your component to your GitHub portfolio.

Confirm the printed part meets all stipulations (size, height, no overhangs, PLA/PETG, print time).

<img width="4032" height="3024" alt="IMG_7810" src="https://github.com/user-attachments/assets/90caf34f-a83e-4a29-aac5-031861f7adec" />

<img width="4032" height="3024" alt="IMG_7813" src="https://github.com/user-attachments/assets/01f68b82-ee8f-4483-841f-27e554c29ae7" />

<img width="3024" height="4032" alt="IMG_7812" src="https://github.com/user-attachments/assets/ae1b678e-c376-486e-b193-b7dc5fe50179" />

<img width="3024" height="4032" alt="IMG_7809" src="https://github.com/user-attachments/assets/a83bdd5d-b230-4a4b-89ed-882ff1d3bb7b" />

<img width="3024" height="4032" alt="IMG_7783" src="https://github.com/user-attachments/assets/b7ab1045-0d1a-400c-89c8-ac573bc444ef" />


https://github.com/user-attachments/assets/9c804972-578a-4965-b6be-2a3efdc43660

This is a quick video of our print process. It does show the orientation of our designs and the Triangles in-fill patter that we chose. 


## Lessons Learned:

Detailed lessons learned throughout the process, the more detail the better. Which includes detailing any mistakes throughout the process and how you fixed them.

Actual time it took from start to finish, and resources.

What would happen if you scaled this decision up? If your infill percentage or wall thickness choice were applied to a structural or safety-critical part instead of a small desk object, what would the consequences of getting it wrong be?

What mistake did you catch, and what mistake might you not have caught? Detail an error you found and fixed. Then, more importantly: what's one flaw in your design or process that could have gone to print undetected, and what would need to change (in your process, not just this part) to catch it next time?

How does this connect to a real product decision? Identify a consumer or industrial product where infill strategy, wall thickness, or material choice affects user safety (it doesn't have to be 3D printed). Briefly explain the parallel.

For this second small print, I've learned that to get a good print, the orientation of the design has to be flat with the surface in order to get a smooth print. Another issue that we ran into was that the file was under the wrong printer setting, which caused an error with the file. Me and my partner had to export the file again with the correct Printer setting. This was a quick fix for our project, after this our print process went smoothly. The print took about 30-40 minutes to complete because the 3D printer takes time to warm up and get set before it is ready to print. If I scaled the design up, the print time will be longer because the overall size of the print will be larger. 

