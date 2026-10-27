# A9 – Laser Cutter

## Objective

The purpose of this lab is to use the laser cutter to create different types of fits and build a construction kit to demonstrate that we measured kerf. In this lab I will be working in a group with Ethan Cornett, and Morgan Gregory. 

## Analyze

Step 1: Before we started to design anything we needed to measure the average thickness of the material. The material thickness is listed below:

Sheet 1: 0.105 in - 2.667 mm

Sheet 2: 0.108 in - 2.7432 mm

Sheet 3: 0.107 in - 2.7178 mm

Average: 0.107 in - 2.7178

Step 2: We needed to also measure the kerf of the laser cutter. We are going to cutting a square of 20 mm x 20 mm.

Nominal Measurements: 20 mm x 20 mm

Measured Results: 19.98 x 19.9

Kerf: 0.1 mm x 0.02 mm 

Step 3: Now that we have the kerf we need to make a fit test to decide what clearance works best. We will do one fit that is below the clearance making it tight,  one that is the clearance we calculated, and one that is above the clearance to make it loose.

<img width="844" height="429" alt="image" src="https://github.com/user-attachments/assets/33551b9b-1163-49ee-b44a-69e73a1e1620" />

For the fit test we started with the starting point in the top left corner to be the origin and then made a relative shape of the fits. 

<img width="712" height="343" alt="image" src="https://github.com/user-attachments/assets/83693fcf-df8c-4320-879c-f4db4ac5f483" />

The fit on the far left is the tight fit. For the calculations of the tight fit we did:

Tight Fit: D = taverage + x0 - Kx - .05 mm

Where K is the kerf and D is the clearance or distance between the pegs.

For the tight fit this turned out to be D = 2.718 mm + 10 mm - .10 mm - .05 mm = 12.568 mm

<img width="682" height="335" alt="image" src="https://github.com/user-attachments/assets/74759f80-b611-4ef9-850c-db214147e8b2" />

The middle fit is the calculated fit. The calculations for the "normal" fit is below. 

Normal Fit: D = taverage + x0 - Kx

For the normal fit this became D = 2.718 mm + 22.568 mm - .10 mm = 25.186 mm

<img width="778" height="401" alt="image" src="https://github.com/user-attachments/assets/d7472b4d-6410-42e1-8b40-59e4db7d58f6" />

Lastly on the far right it is the loose fit. The calculation for the loose fit are below using the same formula as the other two fits. 

<img width="417" height="206" alt="image" src="https://github.com/user-attachments/assets/75a84f52-261e-45e6-ad76-9e2c9ed758e6" />

This is the final design of our fit test. Each fit has a 20 mm depth.


## Decide

<img width="4032" height="3024" alt="unnamed" src="https://github.com/user-attachments/assets/3a924d9f-dca2-4103-8bf1-c9cf83acda17" />


The fit test showed that the best fit has a 0 to 0.005 mm range to take in account for kerf. We chose to do a clearance value of 0.002 mm. This is to give the parts enough room to slide together but it doesn't mean they will come apart. 

## Design 

For our designs we decided to do a triangle, square, and a tri-pod shape. These will fit together to make a unique structure. 

First I made the triangle in SolidWorks as a part. 

<img width="683" height="702" alt="Screenshot 2026-10-26 122851" src="https://github.com/user-attachments/assets/ebe70de6-d4e4-4fa8-bcb7-9620b22737e1" />

<img width="915" height="883" alt="Screenshot 2026-10-26 123927" src="https://github.com/user-attachments/assets/29fa94ef-79de-4395-8060-0eca1ee2116b" />

I made it an equilateral triangle then extruded the slots just to get the basic shape and design down. I did this just to get a good feel on how I wanted each part to look, therefore I did not do this for the rest of the parts. 

<img width="923" height="146" alt="4530dd92-8a7b-49d8-810a-d335219a35e9" src="https://github.com/user-attachments/assets/cef8ba41-7777-413b-9fdd-6a0621d71946" />

To begin the actual design we put the parameters into SolidWorks to ensure an even design. 

<img width="892" height="645" alt="23c9136d-8d9f-44d7-8e5a-35d1cde45768" src="https://github.com/user-attachments/assets/f511928e-a41e-4a1f-982b-4236666f46cb" />

First is the square shape. The x and y kerfs were accounted for in the process and all of the sides have equal lengths and distances. 

<img width="813" height="603" alt="95f67fdc-22c6-4368-8d1b-fc2b916337b0" src="https://github.com/user-attachments/assets/6150d72a-6bca-417f-a9b7-8938b55b4234" />

Next the same thing was done with the triangle piece. 

<img width="813" height="603" alt="95f67fdc-22c6-4368-8d1b-fc2b916337b0" src="https://github.com/user-attachments/assets/dec4d2f6-0857-4a4c-a602-3503ccbbd388" />

The same thing was done for the plus shaped piece. 

<img width="862" height="808" alt="1e08a7de-4694-44a9-9987-c81d7834584e" src="https://github.com/user-attachments/assets/e372cb0b-ef30-4b41-8067-78728ff38a21" />

## Manufacturing

To use the laser cutter we used these steps shown to us by a staff member at the SFL.

1. Open all vents to allow flow (Make sure handles are parallel)
2. Turn on pump beneath printer
3. Turn on printer
4. Center Let printer auto align
5. plug printer into computer
6. Use ctrl + P to print in inkscape
7. Send it to the Epilog cutter (select the material settings)
8. Wait for cutter to finish after pressing start
9. Wait for most of the smoke to leave
10. Open once it is safe and retrieve part.

These are the settings for the laser cutter:

| Setting                              | Kerf Coupon | Fit Coupon | Final Cut |
|--------------------------------------|-------------|------------|-----------|
| Laser cutter (#4)                    | #4          | #4         | #4        |
| Material type                        | wood        | wood       | wood      |
| Nominal thickness                    | 1/8th inch  | 1/8th inch | 1/8th inch|
| Measured thickness (mean)            | 2.709 mm    | 2.709 mm   | 2.709 mm  |
| Speed                                | 20%         | 20%        | 20%       |
| Power                                | 100%        | 100%       | 100%      |
| Frequency or PPI (if applicable)     | 20%         | 20%        | 20%       |
| Number of passes                     | 1           | 1          | 1         |
| Focus method and how you confirmed it| Vector      | Vector     | Vector    |
| Air assist on? Exhaust on?           | Yes         | Yes        | Yes       |
| How you set origin and alignment     | Auto focus  | Auto Focus | Auto Focus|

We ended up using the same settings for the fit test and the final cut 

<img width="596" height="772" alt="a8c7a498-c1f4-43dc-add3-fe71e7b73fb2" src="https://github.com/user-attachments/assets/bd0fbf73-1b70-47f1-9863-2a707d42cc47" />

This is all of our shapes printed out separately. 

<img width="4284" height="5712" alt="IMG_1682" src="https://github.com/user-attachments/assets/9cf9d2bb-36d3-405d-8068-f8a29146a3f7" />

This is the parts all put together.

<img width="3024" height="4032" alt="IMG_1683" src="https://github.com/user-attachments/assets/45581ad6-a7ad-4cd5-81c3-ca237a72a240" />


## Lessons Learned

There were many lessons learned in this project. As someone who had little knowledge about how to use a laser cutter I found it interesting to learn how to use it and 
