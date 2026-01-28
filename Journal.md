1/21

OpenRocket Model

So I worked on creating a rough idea of my rocket in OpenRocket, I reasearched through nose cone shapes and fin shapes to find the best one and finalized them into OpenRocket after around 2 hours, I have to start reasearching on avionics

3d CAD nose cone
I finished the 3d model for my Nose cone and started reasearching on how to design an proper avionic bay for my rocket. I've also started reasearch on an GPS made of Arduino Nano.


1/22

Reasearched Avionics Components

I reasearched on how to build my own avionics and what to put in it, 
I decided with using a LILYGO TTGO T-Beam (v1.1) and solder a BMP280 Barometric Sensor to track altitude, The LILYGO board will also be used to track GPS location to find the rocket after it lands, Im planning to also add a beeper but im not sure yet.
Im also going to connect an ESP32-Cam to a shared power rail to reduce weight of more parts, I'm still working on the final schematic for this whole avionics after which I will 3d design a CAD avionics bay.

1/23

Avionics Schematic

So, today I drew a schematic for my avionics it took a while to fully understand everything but after I did I was able to draw this sketch to how the wires will be soldered when I get them. The black wires are Ground for alitmeter and Camera, the 2 red wires sned power to the altimeter and camera, freen sends altiude data, and the Blue wire is the timing for the data. I'm going to reasearch more into how I can maximize these boards to get more data.  


I'm almost done with my avionics bay, I'm going to make a render of how it will all look soon ,I also gotta refresh on soldering because it has been a long time since I last did. 

1/24

3d CAD Avionics Bay

Today I made some good progress by finishing the Avionics bay, Instead of starting from scratch I found a similar avionics CAD model in thingiverse and i modified it to my needed specs. It took some trial and error, but it was satisfying to see the whoel thing come together nicely.  

While doing this I realized that the ESP-32 Camera I was planning to buy runs on 2.8v instead of the 3.3v i taught it ran on. The camera on the baord is a OV3660 which runs on 2.8V not 3.3V, because of this it could cause to board to overheat without proper ventialtion, I initally though to make a built in fan but that would take up space and weight. So I found a workaround by purchasing and 0V2640 camera on Aliexpress I can swap them to make the voltages match.

1/25

Rocket Rework and Fin Design Reasearch

So just some basic reasearch today, I extended the rocket to 110 cm, I went with the clipped delta shape for my fins but im still deciding between that or I make my own custom shape because I need to cut the corner of the fins so that when the rockets lands it wont land on the fin snapping it. I'm most likely going to design my own but we'll see.


Today was a small day but I going to focus on finalizing everything and making a rendering of the rocket with the livery and finish my BOM so I can get my project reviewed. 

1/26

Full Rocket 3d CAD model

So I made a full 3d CAD model of my Strato Rocket today, and I realized while making this that after I had updated the dimensions of my rocket in my previous journal I hadn't updated my older files containing my nose cone and Avionics Bay, So I went back and changed all the dimensions to match up correctly to make sure nothing wrogn happens during the printing process. I decided that my livery is going to be blue and white and I have to work on the rendering. 
![Screenshot 2026-01-26 214504](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6OTI1OTksInB1ciI6ImJsb2JfaWQifX0=--23e285f8fe2fe9630dc6699d278ee7ed887ea6a1/Screenshot%202026-01-26%20214504.png)
I also updated my BOM for when I submit this design, I'm probably going to do a bit more reasearcha dn refine everything and finish my Github repository by uploading all my files and I should be good to submit for a grant. I totaled the costs and right now and its coming in tier 2 but it probably might go up a little but we will just have to see! 
