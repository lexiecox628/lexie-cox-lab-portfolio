# A5 – Design a Snap Fit

## Objective
This assignment I was told to create a snap fit using the constraints first by hand and then design it in CAD. The snap fit should fit together snug and not slip out unless some force is on it. 

## Modeling 

For the first portion of this project I needed to make a part of the snap fit that will undergo the bending and stress. This is so when the design goes into the 3D print I know it will work and I can design it more parametrically rather than designing it blind on CAD. 

<img width="1428" height="769" alt="image0 (2)" src="https://github.com/user-attachments/assets/d37ba4f6-e206-4f02-9d79-63de7a57b2f1" />

First I listed the knowns and unknowns of the design. I chose to print with PLA so I chose a common PLA Young's Modulus and yield strength. 

<img width="1428" height="843" alt="image1 (2)" src="https://github.com/user-attachments/assets/3b3f4af4-2e37-4e52-9ed3-38a06e1d08ff" />

Since I picked the base and height values I just needed to find the length of the beam. 

<img width="665" height="265" alt="image2 (2)" src="https://github.com/user-attachments/assets/c2ebc7e9-f8d8-4600-8e3d-54a739ea137e" />

Then I created a free body diagram to show my measurments.

<img width="867" height="956" alt="image3 (2)" src="https://github.com/user-attachments/assets/59d60dc1-e81e-44b5-bac2-549c6ec167e6" />

To make sure that my design would pass under the constraints I chose I tested out the different types of stresses it will endure to make sure that the max stress was never passed. 

## 3D Printing and test

<img width="930" height="423" alt="Screenshot 2026-09-21 192639" src="https://github.com/user-attachments/assets/f108def4-8432-4a93-b6e7-6d4e70fd5923" />

I started with the parameters that I calculated because I knew these would not change throughout the entire process.

<img width="961" height="717" alt="Screenshot 2026-09-21 203641" src="https://github.com/user-attachments/assets/039ab9af-07bc-4394-af82-2c51d50d666b" />

Then I made the basic design of the shape I wanted. 

<img width="550" height="390" alt="Screenshot 2026-09-22 110558" src="https://github.com/user-attachments/assets/612bf0dd-b75f-43a5-a233-6d4aa780cc6a" />

Here are the final constraints. I decided to go with a right triangle instead of the other one because I felt that it would hold it place better. 

<img width="815" height="998" alt="Screenshot 2026-09-21 214425" src="https://github.com/user-attachments/assets/7a0986ad-ef24-47b6-99a5-dae21066963a" />

Then I made a basic shape for the thing to snap into.

<img width="722" height="572" alt="Screenshot 2026-09-21 214216" src="https://github.com/user-attachments/assets/48b1bc4c-b262-466f-a3c2-2ea1530dfe09" />

Originally I did this cut into it but then I realized it would not stay in place with how I designed it. 

<img width="728" height="952" alt="Screenshot 2026-09-21 222021" src="https://github.com/user-attachments/assets/ebc30814-64a5-42cf-8a17-e3df19a55cb2" />

This is what my second cut was so that the thing would snap into it. 

<img width="725" height="922" alt="Screenshot 2026-09-22 104848" src="https://github.com/user-attachments/assets/261b4479-3fa7-4689-a15d-58e215e3df53" />

Before I was about to print I realized that the cuts I made on the second part were too high so I could not snap it in or out so I moved them down.

<img width="467" height="452" alt="Screenshot 2026-09-22 101028" src="https://github.com/user-attachments/assets/379109a7-4584-46f3-a4e2-24f83ff3b660" />

This is one of my prints that ultimately failed. It ended up being too far apart so the snap fit would not stay together.

<img width="3024" height="4032" alt="IMG_1456" src="https://github.com/user-attachments/assets/73ad3b4d-f59f-4735-af26-2c42f456337a" />

It also deformed too much and would not snap back into its original place. 

<img width="828" height="832" alt="Screenshot 2026-09-22 114207" src="https://github.com/user-attachments/assets/4fa1dcb9-6917-4c77-b06f-3fa10e39a88b" />

Ultimately I moved the holes down more and I fillet the corner where it would be coming in and out since it was hard to take in and out. 

<img width="633" height="716" alt="Screenshot 2026-09-22 115113" src="https://github.com/user-attachments/assets/1de5eed9-94df-4cd5-a279-ba9d1619d0f7" />

This was my second print in prusa slicer.

<img width="502" height="957" alt="Screenshot 2026-09-22 115315" src="https://github.com/user-attachments/assets/cf6a0d31-2aeb-4663-87c9-d5fcd3ca1347" />

<img width="430" height="397" alt="Screenshot 2026-09-22 115319" src="https://github.com/user-attachments/assets/dec5bcec-94a6-425d-9da7-845a1f383ab6" />

Here is the time and print settings.

<img width="595" height="205" alt="Screenshot 2026-09-21 215142" src="https://github.com/user-attachments/assets/f500cfae-9e23-4d55-a3e8-d98fd791b3b7" />

I decided to use a gyroid filling to make it more flexible and increase the fill density to 20%.


## Communicate

This assignment took me a total of 8 hours to complete. 
