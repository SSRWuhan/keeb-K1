## time spent: 19 Minutes, 24 Seconds

This time I made the folder for containing everything for this project. Also, i opened up KiCAD and 
started working on making the keyboard. I didnt do much just placed the raspberry pi pi pico and some switch diode pairs 
in the schematic.

![Schematic](photos/photo%201.png)

## time spent: 55 minutes, 19 seconds

Well, things went a little sideways. When started to wire up all the switches into a grid I realized that
they were not aligned properly. So, I then had to manually correct all of them to get them to finally
connect to the wires. I so far managed to connect all the rows and 7 of the 17 columns connected.
Connecting will be a breeze.

![Schematic](photos/photo%202.png)
## time spent: 1hour, 10 minutes, 47 seconds

I have finally finished wiring up every single switch to the matrix, assign footprints and annotate all the components.
Now, I have started on making the pcb, but as it seems I guess I will have to manually place
all switches in the right order and then satrt placing all the other components next. I was able to organize about 
80% all keys so far. Also, I decided on adding a joystick to my project to simulate a mouse.

![PCB](photos/photo3.png)

## time spent: 39 minutes, 54 seconds

I first sorted all the keys in the PCB accordinng to their postions in the matrix. Then I finally began organizing everything 
neatly on the Pcb for the final touches.

![PCB](photos/photo4.png)

## time spent: 1hour, 6 minutes, 4 seconds

I finally finished organizing every single switch. I have started to organize the diodes. I
probably have done about 40% of the wor by now. This could have been done if it wasn't for the fact that I had to 
do this manually.

Future me: Turns out there actually was a faster way to do this by using grids and selecting the top of one the
switches. Also I could have just placed them without leaving a little gap between them since the schematic already
accounts for that. 

![PCB](photos/photo5.png)

## time spent: 1hour, 8 min, 7 sec

I finished setting up all the diodes, reaannotated everything and finally started routing the pcb.
It took a while to set up the matrix as I wanted.

![PCB](photos/photo%206.png)

## time spent: 56 minutes, 53 seconds

While working on the PCB realized that the joystick footprint I was using was not the right one, so I am now replacing 
it with a 4 pin connector. I also the been re rounting everything for the 3rd time now, since I keep messing up 
the spacing between the keys and the pico. Hopefully from here onwards it will be smooth sailing.

![PCB](photos/photo%207.png)

## time spent: 1hour

I am finally done making the PCB. But, unfortanately the Cherry MX switches dont have a 3d model attached to 
them, so I am now manually attaching them.

![PCB](photos/photo%208.png)

## time spent: 50 minutes, 8 seconds

I have completed assigning all the Cherry MX switches with their 3D models and exported stl and gerber files.

![PCB](photos/photo%209.png)

## time spent: 2 hours, 11 minutes, 10 Seconds

I have started working on making the case for the keyboard. So far I have exported the PCB model as a 
reference even though it took me a few tries since it was my first time using a another model in CAD directly as a
reference. After that I modeled the bottom, walls and top of the case. I am currently drawing boxes around the keys 
to cut an opening for the keys.

![PCB](photos/photo%2010.png)

## time spent: 1 hour, 22 minute, 4 seconds

I have finished making all the holes for the keys. But I realized after that I need to cut a bigger rectangle for the spacebar
since I need it open so I can place stbailizers fot it. After that I began working on the hole for the joystick. Since, I 
didn't have the 3d model of it on the PCB so, I got the measurements from a joystick model in GrabCAD.
After that Started working on the usb hole, but thankfully I realized that the pico didn't have enough space. I then 
proceaded to make a little compart for it and rounded the edges of it for asthetics. I am now done with cutting the hole and 
now just need to round up the edges.

![PCB](photos/photo%2011.png)

## time spent: 1hour, 50 minutes, 29 seconds

Well it longer than expected to make the hole. At first I realized that the outer plastic layer could interfear with the
usb plugging in properly so I first made a big rectangle and then made a ractangular hole for the micro usb. I also rounded up 
the edges with the fillet. After this I began working on making holes for the screws and threads. It was a tight fit. I then split the 
top and bottom of the case into 2 parts. Then I eported everything from Onshape.

![PCB](photos/photo%2012.png)

## time spent: 41 minutes, 40 seconds

I wrote a basic firmware for the keyboard with 1 properly made layer. I plan on expanding this later when I have 
physically built the keyboard, along with completing vial.json then.

![PCB](photos/photo%2013.png)

# Total time: 14 hours, 11 minutes, 59 seconds
