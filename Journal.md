---
title: keeb-K1
github: https://github.com/SSRWuhan/keeb-K1
description: This is my keyboard design for the KEEB program from Hack Club.
created_at: 2026-08-06
total_time: "14h 8m"
---

# August 6, 2026: The start
<!-- fabricate:entry 1124 -->

This time I made the folder for containing everything for this project. Also, i opened up KiCAD and 
started working on making the keyboard. I didnt do much just placed the raspberry pi pi pico and some switch diode pairs 
in the schematic.

![Schematic](https://fabricate.hackclub-assets.com/ee1bf215f25879711fa25ec6230a5453eecca9d735e98310143bedd815f8351e/image-png/photo%201.png)

**Total time spent: 19 Minutes, 24 Seconds**

**Total time spent: 19m**

# August 8, 2026: Manually aligning every switch diode pair
<!-- fabricate:entry 1125 -->

Well, things went a little sideways. When started to wire up all the switches into a grid I realized that
they were not aligned properly. So, I then had to manually correct all of them to get them to finally
connect to the wires. I so far managed to connect all the rows and 7 of the 17 columns connected.
Connecting will be a breeze.

![Schematic](https://fabricate.hackclub-assets.com/fec7885b43f0785ed0e91dce5785d37b2f4d22dc5c3a4603370b2922a3e5106c/image-png/photo%202.png)

**Total time spent: 55 minutes, 19 seconds**

**Total time spent: 55m**

# August 10, 2026: Ending of the schematic, beginning of the PCB
<!-- fabricate:entry 1126 -->

I have finally finished wiring up every single switch to the matrix, assign footprints and annotate all the components.
Now, I have started on making the pcb, but as it seems I guess I will have to manually place
all switches in the right order and then satrt placing all the other components next. I was able to organize about 
80% all keys so far. Also, I decided on adding a joystick to my project to simulate a mouse.

![PCB](https://fabricate.hackclub-assets.com/8c6d11ef90a5ede9d76bd1817237543fca57c6e41824f7de18159c195c33acb9/image-png/picture3.png)

**Total time spent: 1 hour, 10 minutes, 47 seconds**

**Total time spent: 1h 12m**

# August 12, 2026: Finishing the positions of the switches
<!-- fabricate:entry 1127 -->

I first sorted all the keys in the PCB accordinng to their postions in the matrix. Then I finally began organizing everything 
neatly on the PCB for the final touches.

![PCB](https://fabricate.hackclub-assets.com/677ab5b6800884d0d6205f6cb8ae6ceaf416470e512864e2086c410fd640bef3/image-png/picture4.png)

**Total time spent: 39 minutes, 54 seconds**

**Total time spent: 39m**

# August 15, 2026: Starting the placement of diodes
<!-- fabricate:entry 1128 -->

I finally finished organizing every single switch. I have started to organize the diodes. I
probably have done about 40% of the work by now. This could have been done if it wasn't for the fact that I had to 
do this manually.

Future me: Turns out there actually was a faster way to do this by using grids and selecting the top of one the
switches. Also, I could have just placed them without leaving a little gap between them since the schematic already
accounts for that.

![PCB](https://fabricate.hackclub-assets.com/64ced7acc709cf9b0f82c649239ca2b438e9cc839485f31d9cd31d0d419732a8/image-png/picture5.png)

**Total time spent: 1 hour, 6 minutes, 4 seconds**

**Total time spent: 1h 6m**

# August 18, 2026: Finished the placement of diodes
<!-- fabricate:entry 1129 -->

I finished setting up all the diodes, reannotated everything and finally started routing the pcb.
It took a while to set up the matrix as I wanted.

![PCB](https://fabricate.hackclub-assets.com/f4095adad9b70cf1f0a20f32a9a208e405b47ae70085c9c4578cb54eb6802659/image-png/photo%206.png)

**Total time spent: 1 hour, 8 minutes, 7 seconds**

**Total time spent: 1h 6m**

# August 20, 2026: Fixing The PCB
<!-- fabricate:entry 1130 -->

While working on the PCB realized that the joystick footprint I was using was not the right one, so I am now replacing 
it with a 4 pin connector. I have also been re rounting everything for the 3rd time now, since I keep messing up 
the spacing between the keys and the pico. Hopefully, from here onwards it will be smooth sailing.

![PCB](https://fabricate.hackclub-assets.com/1ba689504dd0bfa423ac69274ebb498ac9e2407c92a5543ca3aec33e8e7eb2ed/image-png/photo%207.png)

**Total time spent: 56 minutes, 53 seconds**

**Total time spent: 56m**

# August 22, 2026: The manual placement and adjustment of 3D models
<!-- fabricate:entry 1131 -->

I am finally done making the PCB. But, unfortanately the Cherry MX switches don't have a 3D model attached to 
them, so I am now manually attaching them.

![PCB](https://fabricate.hackclub-assets.com/4556ea407b774af65423460f3ed468fb3536cbbdf71b2c4591006221812b38fa/image-png/photo%208.png)

**Total time spent: 1h**

# August 24, 2026: The completion of the PCB
<!-- fabricate:entry 1132 -->

I have completed assigning all the Cherry MX switches with their 3D models and exported STL and Gerber files.

![PCB](https://fabricate.hackclub-assets.com/f318699aee512327b8f88380e2ebc365e1384bbf0973428da84edb11cac4010c/image-png/photo%209.png)

**Total time spent: 50 minutes, 8 seconds**

**Total time spent: 50m**

# August 28, 2026: The beginning of the case
<!-- fabricate:entry 1133 -->

I have started working on making the case for the keyboard. So far I have exported the PCB model as a 
reference even though it took me a few tries since it was my first time using a another model in CAD directly as a
reference. After that I modeled the bottom, walls and top of the case. I am currently drawing boxes around the keys 
to cut an opening for the keys.

![PCB](https://fabricate.hackclub-assets.com/f95a1370ea353573620e06c3403c9f1f76c0686c42547ac242fcc48e7a02ec21/image-png/photo%2010.png)

**Total time spent: 2 hour, 11 minutes, 10 Seconds**

**Total time spent: 2h 12m**

# September 4, 2026: The refinement of the case
<!-- fabricate:entry 1134 -->

I have finished making all the holes for the keys. But I realized after that I need to cut a bigger rectangle for the spacebar
since I need it open so I can place stabailizers fot it. After that I began working on the hole for the joystick. Since, I 
didn't have the 3d model of it on the PCB so, I got the measurements from a joystick model in GrabCAD.
After that Started working on the usb hole, but thankfully I realized that the pico didn't have enough space. I then 
proceaded to make a little compartment for it and rounded the edges of it for asthetics. I am now done with cutting the hole and 
now just need to round up the edges.

![PCB](https://fabricate.hackclub-assets.com/005d7dd16301644b46a9d3edc489f90fd6655ffe663865de80070073c5c52b74/image-png/photo%2011.png)

**Total time spent: 1 hour, 22 minutes, 4 seconds**

**Total time spent: 1h 24m**

# September 7, 2026: The secondary stage of refinement and the ending of the case
<!-- fabricate:entry 1135 -->

Well it took longer than expected to make the hole. At first I realized that the outer plastic layer could interfear with the
usb plugging in properly so I first made a big rectangle and then made a ractangular hole for the micro usb. I also rounded up 
the edges with the fillet. After this I began working on making holes for the screws and threads. It was a tight fit. I then split the 
top and bottom of the case into 2 parts. Then I exported everything from Onshape.

![PCB](https://fabricate.hackclub-assets.com/c6a2588466c98c8ca7148d22990e0f0785522c01fd4a1365018d9cd17df5e8dd/image-png/photo%2012.png)

**Total time spent: 1 hour, 50 minutes, 29 seconds**

**Total time spent: 1h 48m**

# September 13, 2026: The creation of the Firmware
<!-- fabricate:entry 1136 -->

I wrote a basic firmware for the keyboard with 1 properly made layer. I plan on expanding this later when I have 
physically built the keyboard, along with completing vial.json then.

![PCB](https://fabricate.hackclub-assets.com/465fd72048676a6cf8e2dd8693a4f4991d350a0d12489c71e30a3cc4620143e2/image-png/photo%2013.png)

**Total time spent: 41 minutes, 40 seconds**



## Total time: 14 hours, 11 minutes, 59 seconds

**Total time spent: 41m**
