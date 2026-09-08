## Lab 3 - Print something small

#Design

I wanted to design something that allowed me to refine my skills on solid works and that would be within the constraints and time limit. I used solid works because I knew that it was one of the most popular in the in the engineering field. 

<img width="352" height="352" alt="Screenshot 2026-09-03 095448" src="https://github.com/user-attachments/assets/8e208cf9-11b8-487b-a3b3-fe36b749713e" />

I started off with a simple circle as the base and a good starting point. 

<img width="653" height="645" alt="Screenshot 2026-09-03 101133" src="https://github.com/user-attachments/assets/2acba2ed-5173-4c1e-9c02-79bebab3e4b6" />

Then I added the petals which are just made of circles of equal lengths to make them symmetrical. 

<img width="828" height="777" alt="Screenshot 2026-09-03 101331" src="https://github.com/user-attachments/assets/ec8085e6-73bd-4378-a974-5e243df1e804" />

After that I extruded the sketch to make it a part that is 3D.

<img width="1027" height="915" alt="Screenshot 2026-09-03 101415" src="https://github.com/user-attachments/assets/d8ef23af-00b0-484a-9048-890b887f6211" />

Then I sketched out a circle in the middle to create the hole in the middle. 

<img width="1043" height="943" alt="Screenshot 2026-09-03 101936" src="https://github.com/user-attachments/assets/83dba0b9-0075-43c9-a799-d8d2844c63be" />

This is what it looked like after the part was cut out.

<img width="1077" height="923" alt="Screenshot 2026-09-03 102017" src="https://github.com/user-attachments/assets/a2648fa1-e7bd-4672-97e9-8cdc28d9ee8d" />

I decided to make the flower a keychain so I added another hole to the top of the flower in the middle of the top petal. 

#Research

The Hilbert curve infill pattern is a continuous pattern of rectangles but the rectangles never connect and never crosses. It helps reduce internal stress but it increases the time for the print because of its pattern. Example of a Hilbert curve below. 

<img width="720" height="960" alt="hil2" src="https://github.com/user-attachments/assets/d1e2c4c5-37b9-4620-8c06-9c77fd3568d5" />

The grid infill pattern is squares that are printed in both directions in each layer. It is one of the fastest and more simple patterns but it can cause a print failure because of the change in directions. Example of a grid pattern below.

<img width="1536" height="1152" alt="mrizkafinal-1-1536x1152" src="https://github.com/user-attachments/assets/5e119397-b822-4d2c-81cc-a01cf75dae1f" />

Another infill pattern is concentric. This pattern makes the perimeter smaller and smaller in the middle. This pattern is not the best structurally but it can be good for more flexible parts. An example below is provided. 

<img width="1536" height="1152" alt="concentricfinal-1-1536x1152" src="https://github.com/user-attachments/assets/5b3b1bc2-046a-4ca3-bc0e-e04c82e516b0" />

Lab notes: 
Infill - Honeycomb pattern, Gyroid Pattern, Infill patterns were not invented to 3D printing it was borrowed from other engineering basis. 
Wall thickness - solid layers separate from infill. More perimeter loops is more solid material at the part's boundary,
Rafts, Skirts, and Brims - Rated is under the part that connects uneven contact areas. Skirt and outline around the part that doesn't touch it, makes sure the nozzle goes around how its suppose to. Brim, Attached to the edge is similar to skirt but is actually connected to the part.

Different infill percentages can affect many parts. Typically the higher the infill percentages the increased strength, stiffness, and weight. There are many different infill patterns and all have their advantages and disadvantages. Some can make the part more durable, flexible, and weight. 

#Preprocessor and Printing

<img width="637" height="443" alt="Screenshot 2026-09-03 102508" src="https://github.com/user-attachments/assets/a586ca3b-e716-4f12-9684-ef33f12f247c" />

This is what it looked like on Pursaslicer before it was sliced. I did this orientation because it was a flat bottom with no gaps. 

<img width="426" height="252" alt="Screenshot 2026-09-06 153101" src="https://github.com/user-attachments/assets/c8e320b8-fb8c-47f2-8947-239c53bea089" />

These are the size and coordinates of my print. I scaled mine to almost 200% because I didn't want it too small to where you couldn't tell what it was. 

<img width="503" height="236" alt="Screenshot 2026-09-03 130939" src="https://github.com/user-attachments/assets/d62be6cd-1aee-46d0-aa23-5af388fa31f5" />
<img width="602" height="236" alt="Screenshot 2026-09-03 125357" src="https://github.com/user-attachments/assets/65b036a9-4779-4244-b91f-241324ce632b" />
<img width="627" height="185" alt="Screenshot 2026-09-03 125403" src="https://github.com/user-attachments/assets/490e0ef5-cc6e-4334-a584-cc1efe276698" />

I decided to change the infill and top fill pattern to test them out and see the difference it makes the infill was changed to a gyroid pattern to help with the uniform loads since it is a keychain. The top fill was changed to a Hilbert curve pattern because it reduces the internal stresses. I also increased the fill density to make it more durable. I also added a brim to the outside of my print. I also used PETG because I like how it looked on my last project. 

<img width="707" height="658" alt="Screenshot 2026-09-03 125347" src="https://github.com/user-attachments/assets/2b102dc4-1e2e-4ef4-81df-4f6e6797757e" />

We had to work in groups since there is a limited amount of printers so I worked with Morgan Gregory and Ethan Cornett and these are what the prints looked like on Pursaslicer. 

<img width="417" height="518" alt="Screenshot 2026-09-03 102545" src="https://github.com/user-attachments/assets/2b23090f-991c-4b94-8810-bb6929ceaf06" />

This is what my print looked like after it was sliced.

<img width="437" height="437" alt="Screenshot 2026-09-03 131025" src="https://github.com/user-attachments/assets/13655b2b-cdf7-40f7-a3bb-50d55e8210ec" />

Pursaslicer shows us the time split up into what the printer will be doing. Overall it says the print will take 19 minutes.  

#Print

Here is the final print 

<img width="3024" height="4032" alt="IMG_1213" src="https://github.com/user-attachments/assets/d3c25b06-21ec-4be4-8e43-caa0de90ebdf" />



https://github.com/user-attachments/assets/45c47612-23a7-4db6-b0ec-4e64992b5644



#Lessons Learned

The biggest mistake I made was that the keychain hole was too small to fit a keyring. Therefore now it is just a flower. I also realized that the hole was too far up to the edge of the design. This could have made the design incomplete or made it too thin to the point of breaking off. 

If the infill percentage or wall thickness was off on a critical part this could cause the whole project to fail because of it cracking. This could lead to damage to surrounding objects or cause harm to people. One design I also caught was that it was not thick enough. I had made it 0.2 millimeters instead of inches. This would have caused the print to be too brittle and probably would have snapped in half when taking it off of the plate. One product is a helmet. It is important to pick the right material to prevent something going into the helmet and so it doesn't shatter when it hits something. However you want the inside to also be comfortable but protective. The wall thickness of the outside can't be too thin or else it will be brittle but it can't be too thick because it will be heavy.   

#Resources

https://help.prusa3d.com/article/infill-patterns_177130 

