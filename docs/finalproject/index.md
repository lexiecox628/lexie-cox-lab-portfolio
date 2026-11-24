# Final Project

## Objectives

The purpose of this project is to incorporate things we have learned from this semester to solve a real world problem. For this project we have to use two of either SLA, Laser Cutter, and/or the FDM printer. We will go through the spiral design process that will bring us to our final product. 


## Part 1

### Research

#### Spiral Design Process

In the spiral design process there are four main components:

1: Planning - In this stage you are finding all of the goals, requirements, and limits for the project. 

2: Risk Analysis - This stage is where you will look at alternative solutions and list the pros, cons, and any conflicts you may have. 

3: Engineering - In this part of the process you will now design, prototype, and test based on what you learned in the previous two steps. 

4: Evaluation - This is the final step of the process and this is where you will present what your problem is and everything you have learned. You will also present your prototype and all the testing you have done. You will then get feedback on everything. 

The reason it is called the spiral design process is because it doesn't necessarily mean that after you go through the steps that you will have your final design. You will more than likely have to keep repeating the process over and over until your final project is fine tuned. 

#### FDM Anisotropic

The reason the FDM printer produces anisotropic parts is because it stacks on top of each other rather than being one solid part. A hot layer is being placed on top of a already cool layer so it is not fusing together. There also could be air gaps between layers. This is why orientation is so important, it is important to align the tensile and bending loads perpendicular to the z-axis. Different materials also matter. For example in this class we have used PETG and PLA. PLA is more brittle but it melts at a low temperature. PETG is stronger but it is less elastic. 

#### SLA Shrinkage

When using the resin printer the SLA material shrinks anywhere from 1.5% and 8%. This impacts different fits and the overall design of the CAD. The material shrinks when it is getting cured in the UV light. Different materials can change how much it shrinks. However they can be more or less stable at the same time. When designing a SLA part and it has a snap fit or a sliding fit it is important to put tolerances in your design. SLA is more brittle and will not bend easy. It is important to think about wall thickness in this case. 

#### Laser Cut Kerf

When using a laser cutter, the material is getting burnt and dissipates. This means that when the design is getting printed things could be too loose or misaligned. To compensate for kerf it is useful to print out a test piece and then measure what you designed the dimension to be and what it actually is. Then you need to put tolerances in your design so the print does not fail. Another method is to use layer mapping so that you can create custom offsets for the different edges. 

### Problem Definition

#### Wheelchair

People who are in wheelchairs have no room to hold stuff when getting from place to place. Especially if they have to move their wheel chair by themselves. There hands are preoccupied and the only place to put something is in their laps. Using their lap is unstable and can also be unsafe. Things such as bags, water bottles, and so much more. Carrying these things can require additional help but what if they are by themselves or want to be more independent. 

#### Buggy disaster

When you are in a grocery store people tend to bring in a bunch of stuff with them such as a purse, phone, wallet, keys, and a lot more stuff. There is little room to put this stuff in the cart especially if you have a full cart of stuff. Not only is it unorganized and hard to find things different things fall through the holes constantly and they don't tend to stay in one spot. 

#### Desk unorganized

My at home desk can get super crowded when I am trying to do different projects, study, or even just get cluttered from everyday life. I have pens, cords, decorations and everything in between scattered on my desk and even just thrown into drawers. When my desk is like this I feel like a mess and I feel like it drains my focus every time I sit down to do work. 

### Problem Solution

The problem I chose to solve is the buggy disaster. I plan on making an attachment to the cart that will act as a table, have a cup holder, and a pen holder. This will make all of your items more organized and not fall out of the cart. It will also allow you to have some more room inside the cart. I want to solve this problem because I often see people dropping things out of their cart or getting flustered because their stuff is buried under groceries. 

### Concept Development

### Testing Critical Features

In my design I have two features I need to test before fully printing them. One is a sliding fit to extend out my design and to compensate for any difference in cart dimensions. The other is another sliding type fit so the cup holder can attach and reattach. When doing these test I scaled down the designs for time. 

The first one I tested was the extension. I made a basic T design and a box that it will slide through. 

<img width="707" height="677" alt="Screenshot 2026-11-20 011814" src="https://github.com/user-attachments/assets/fe7f1d1a-6f0d-431a-9e3e-292f67a811d8" />

<img width="510" height="427" alt="Screenshot 2026-11-20 012206" src="https://github.com/user-attachments/assets/bd80f0cc-540d-495e-aa97-1909e523b511" />

This design worked out really well and the dimensions allowed it to slide smoothly and allow for the T to have enough room at the end to attach a strap in the final design. 

(Insert Pictures of T)

In my design I wanted to be able to remove the cup holder for ease of storage. For this part I thought it would be interesting to experiment with a different type of sliding fit I have not done before. For this fit the cup holder will have extensions that go into the base of the board and twist to hold in place. 

<img width="693" height="857" alt="Screenshot 2026-11-20 022041" src="https://github.com/user-attachments/assets/35808f48-31fe-4b1e-bb84-6b4b8ba80b30" />

<img width="805" height="622" alt="Screenshot 2026-11-20 025236" src="https://github.com/user-attachments/assets/e7a4ff40-9d81-4fa0-858e-547c5e090946" />


This design in theory worked out really well. During printing I made it too small and in result the supports would not come out of the hole. 

(Insert Pictures of cup holder)


### Video








### Feedback

### Refinment

### Model

The first thing I printed was the hook using the SLA printer. I wanted to use a 3 pronged hook that allowed it to hold multiple things. I also decided for this to be the part that uses the resin printer because I needed it to be more sturdy and have a higher yield strength. Below is the process I used for the hook design. 

<img width="718" height="677" alt="Screenshot 2026-11-24 094843" src="https://github.com/user-attachments/assets/6e10b779-409e-4b14-8710-17ee68fe80cb" />

First I started out by making the basic shape of one of the prongs.

<img width="763" height="636" alt="Screenshot 2026-11-24 095615" src="https://github.com/user-attachments/assets/5003c333-3a71-453a-9e07-ebf92c120998" />

<img width="925" height="901" alt="Screenshot 2026-11-24 095704" src="https://github.com/user-attachments/assets/e53db212-8bf8-4580-9c5d-fd240e274702" />


Then I revolved it to make it a full circle and added a hole for a screw to fit into. 

<img width="1162" height="782" alt="Screenshot 2026-11-24 100646" src="https://github.com/user-attachments/assets/7316473c-e5de-497e-9905-942c0c14fd18" />

Then I made three separate cuts to make the three prongs. 

<img width="633" height="797" alt="Screenshot 2026-11-24 101348" src="https://github.com/user-attachments/assets/26df0df4-dab5-45b7-aca9-071a64bb8d88" />

Finally I added fillets to make sure it was smooth. 

### Prints



### Final Video
