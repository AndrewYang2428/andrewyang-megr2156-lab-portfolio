# A4 – Benchmark a Parameter

## Analyze:

### Benchmark Test: Tolerance Gauge

The Tolerance Gauge tests how accurately a 3D printer can produce the specified tolerances of a printed object. When a tolerance is added to a dimension, it defines the acceptable range in which the actual printed dimension can vary from the designed dimension. This helps evaluate the precision and accuracy of the 3D printer. A model may appear correct visually while still being dimensionally inaccurate because of variations in the printing process. Other external factors, such as temperature, material, printer settings, and the printing process itself, can also affect the final dimensions and overall shape of the model. For this test, I was required to design a tolerance gauge that tested a tolerance of ±0.3 mm, measure the actual dimensions of the printed gauge, and calculate the printer's actual tolerance. The main goal of this design was to determine whether the 3D printer could consistently meet the specified tolerance from the design requirements. These benchmark tests are useful for determining the limits of a 3D printer and identifying areas where adjustments can be made. The results can be used to modify printer settings and improve the printer's accuracy and consistency for future prints.

### Predictions:

Before testing the Tolerance Gauge, I think that the printer tolerance will not be accurate to the 3D model because of the filament used. For the tolerance gauge that I designed, I feel that the most accurate tolerance should be the plus or minus 0.3mm because it is about the average of all of the tolerances on the Tolerance Gauge. There are many different factors that can cause an effect on the tolerance held, like how much the material expands or shrinks, the size of the nozzle, the tolerance level of the printer itself... Since these are tight tolerances, it will be pretty hard to be precise and hold these tolerances throughout the whole print process, but I do believe that it will be around the diameter that I designed it to be. 


## Decide:
### 3D CAD Model:

Picture: CAD dimensions of the base

<p align='center'>
<img width="49.5%" height="2000" alt="Lab_4_Tolerance_Base" src="https://github.com/user-attachments/assets/2c91e375-a58d-4dfb-829f-4465b0c55dd3" />
<img width="49.5%" height="2000" alt="Lab_4_Base_Extrusion" src="https://github.com/user-attachments/assets/408a64e5-a6e7-4ce7-8a41-df8bbc1e2bef" />
</p>

For the base of the Tolerance Gauge, I sketched out an 8mm by 1mm block and extruded it out 2mm to make the base of the Tolerance Gauge. This acts as a platform for the pillars that I designed to make measurements to test the tolerances. 

Picture: CAD dimensions of the gauges

<p align='center'>
<img width="49.5%" height="1020" alt="Lab_4_Tolerance_Gauge" src="https://github.com/user-attachments/assets/70ec75d6-d7e6-4e95-9889-df0767a880df" />
<img width="49.5%" height="1020" alt="Lab_4_Tolerance_Gauge_Extrusion" src="https://github.com/user-attachments/assets/f9afec52-cd7e-4726-a0b4-912c8b955395" />
</p>

For the Tolerance Gauge, I sketched out 5 1mm diameter circles spread out evenly on the top of the base that holds different tolerances ranging from 0.1mm-0.5mm. Then, I extruded the circles 0.5mm out of the base to create the pillars that are used to measure the tolerances. 

Picture: CAD View of Dimension Numbers

<img width="1917" height="1020" alt="Lab_4_Tolerance_Number" src="https://github.com/user-attachments/assets/a1776252-ae4e-4c86-8444-4094ecf23809" />

For each tolerance of the 5 pillars, I extruded out the number of the tolerance on top of the pillars. This allowed for easy distinction of each pillar and the tolerance placed on them. 

Picture: Final Tolerance Gauge

<img width="1917" height="1020" alt="Lab_4_Tolerance_Numbers" src="https://github.com/user-attachments/assets/40b0ac1e-1115-4ce5-a46f-2476c360eaf9" />

This is the Final View of my Tolerance Gauge that I designed to test the 3D printer. 

### Print Process:

PrusasSlicer:

<img width="2559" height="1470" alt="generic_info" src="https://github.com/user-attachments/assets/d41325f6-83d2-40c7-a2d9-0166cb286628" />
<img width="1010" height="200" alt="infill_used" src="https://github.com/user-attachments/assets/fa7f9404-18b4-4ff0-849a-3ae305bd9a25" />

This is the view of our designs in PrusasSlicer as well as the filament type and the sliced information. It also shows the in-fill information for this print as well. The information in these images show the settings that we changed and allows for a clear understanding about how we prepped for the print. 

Start of Print:

<img width="4000" height="3000" alt="20260911_093616" src="https://github.com/user-attachments/assets/d02420bc-98cf-4433-a461-c33c5c6a9be0" />

End of Print:

<img width="4032" height="3024" alt="IMG_7856 2" src="https://github.com/user-attachments/assets/ba2c1190-c5ab-49e3-bb10-225e4967aba3" />

Total Print Time:

<p align='center'>
<img width="49.5%" height="3000" alt="20260911_091324" src="https://github.com/user-attachments/assets/b755b9e0-5c2d-4ac0-9919-cb63f1ec2d24" />
<img width="49.5%" height="3024" alt="IMG_7859 2" src="https://github.com/user-attachments/assets/51a13765-c43a-415d-adcf-8110cc5eda3d" />
</p>

Shown in picture on the left is the time stamp for how long the print will take to complete. It also shows the material that will be used for this print displayed at the bottom of the screen. In the picture on the right, it shows the total time to complete the print. It shows the date and time the print started and the date and time the print ended, the consumed material for the print, and the temperature of the printer during the printing process.  

## Preprocessor:

Detail the reasons why you chose the build parameters in the preprocessor. Note the slice information on PrusaSlicer. Some, not all, questions to answer are outlined below to guide your documentation.

Why did you choose that infill?

For this project, me and my partner Andy printed our designs together, we agreed on the "Grid" in-fill because it was a simple pattern that didn't affect our benchmark test. The Grid in-fill is a default in-fill pattern that is perfect for many designs. It's a very balanced in-fill that allows for a strong structure while being flexible. 

Why did you choose that build orientation?

For my design, I went based off of the reference model shown on Canvas. It is a simple design that allows us to test for the tolerance placed on our designs. 

Did you use supports? If so, how did you add supports in the software?

For my design, I did not need to use supports. 

Did you need to scale? If so, why and how?

Since I made my design in MMGS instead of IPS, I had to scale my design up to be large enough to test for the tolerances. With this re-scale, my dimensions are different, but it doesn't affect the tolerances placed on each pillar. 

Detail any mistakes throughout the process.

For this test, there were some challenges and mistakes throughout the process. A mistake that I made when designing the Tolerance Gauge was following Design Rules for the Tolerance Benchmark Test. I didn't make the tolerances plus or minus 0.3mm at first, so I had to change this and ensure that my numbers on the pillars matched to the tolerance placed on them. During the print process, I forgot to take a quick video of the print, so I had to restart the print to get a quick video of the print process. Since I had to make changes to my design, I was able to capture a quick video as well as ensure my design was correct. 

## Print Artifact:

Picture of Printed Tolerance Gauge:
<p align='center'>
<img width="49.5%" height="4032" alt="IMG_7986" src="https://github.com/user-attachments/assets/cbebe20b-ba87-4cbc-b470-830b8dcb5494" />
<img width="49.5%" height="4032" alt="IMG_7982" src="https://github.com/user-attachments/assets/adf107fc-b8f6-4574-8be1-439b2f7025c0" />
</p>
<p align='center'>
<img width="49.5%" height="4032" alt="IMG_7984" src="https://github.com/user-attachments/assets/c7da947b-e1c6-4e4d-9a34-05c3ea1b0114" />
<img width="49.5%" height="4032" alt="IMG_7993" src="https://github.com/user-attachments/assets/92c05cd2-5b4e-425f-8913-ad5c6d43b8cc" />
</p>

This shows the final print of the tolerance gauge that I designed for the tolerance test. The pillars shown each have a number that represents the tolerance placed on them. Starting from 1 to 5 the tolerance increases by 0.1mm to 0.5mm. This allows us to test and see where the tolerance is most accurate and where the tolerance gives out. Visually it looks like they are all the same diameter with the same tolerance but once it is measured, each pillar will be able to be distinguished. 

Video: 

<img width="800" height="450" alt="Lab_4-ezgif com-optimize" src="https://github.com/user-attachments/assets/540eb492-67f5-44eb-948b-91632d6f41e3" />

## Lesson Learned:

Was the outcome different than what you originally thought?

The outcome of the tolerance gauge was exactly what I thought it would be because I've had some experience with 3D printing with a specific tolerance and it was not very accurate with what I needed. When you are dealing with tight tolerances, it is hard for the 3D printer to hold that tolerance and make it as accurate as you want it to be. I believe that it is possible to dial the 3D printer in to be as precise as possible and also make changes to the material and the nozzle to make it print more accurate as well. 

Compare your result to the FDM row of the class design rules chart. Did your result match, exceed, or fall short of the documented spec, and why?

The results exceeded the documented specs of plus or minus 0.3mm. 

Detailed lessons learned and things you would change throughout the process. You should identify a minimum of four things. Be specific, and use articulate engineering, 3D printing, and design language.

Actual time it took from start to finish.

## Resources

[Design Rules for 3D Printing](https://instructure.charlotte.edu/courses/272053/files/33203768?wrap=1)
