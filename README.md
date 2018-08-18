## Homemade CNC 

### Introduction

This is the second version of my DIY homemade CNC. It's a complete redesign because of some issues that I had with the first one. The main issue with the first version was that the wooden Y axis was getting warped (by moisture I guess). Also the bearings were too small and the aluminium X rails were not strong enough to carry the weigth. That's why I've switched over to use 20mm x 20mm square steel tubes for both Y- and X axis. 

### YouTube video

<a href="TODO" target="_blank"><img src="TODO" 
alt="Click to view: Homemade CNC with 3D printed parts V2" width="500" border="1" /></a>

### Design

I've designed the 3D printed parts with Fusion 360 and used Inkscape for the Y axis drilling template. To control the machine I'm using an Arduino UNO with GRBL firmware and an Arduino CNC Shield. There are plenty of tutorials to find on how to connect and use it so I did not show it in the video. Here are some useful links:

* [GRBL](https://github.com/gnea/grbl)
* [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield/)

### Warning

If you want to build one yourself you can download all the necessary files from the V2 directory but I don't have enough time to give you much support so build it at your own risk! :smiley:

### 3D Printing

The 3D printer I use is an Anet A8. The parts are printed with PLA, mostly 20% infill and 0.2 or 0.4 setting. Use higher infill for parts that must be stronger, for example the stepper motor mounts.

### Cost estimation

* [Link to Google Sheet](https://docs.google.com/spreadsheets/d/e/2PACX-1vQY4hpT6myB3YeNzVlFZfTstJrkYJus8l174NMnyP0J1uP0NMzN-vVNtQ_hvMKP-WXqgEPKxjZSqRSU/pubhtml "Link to Google Sheet")

### Dimensions

Base front multiplex Y panels are 710 x 180 x 22 mm or 28" x 7" x 0.86".
The laminated MDF X Axis side panels are 180 x 370 mm or 7" x 14.4".

The tubes are 20mm x 20mm (0.78") square steel tubes. The length of the Y Axis tubes is 1000mm (40") and the length for the X Axis is approx. 820mm (32"). As an alternative you could also use other dimensions than 20mm x 20mm (maybe even rounded tubes) as long as they are approximately that size.
The Z axis tubes are 15mm x 15mm (0.59") aluminium square tubes, approx. 215mm long (8.5"). You should measure this for yourself, check the video build.

The threaded rods for Y and X rails are 8 mm (0.31") stainless steel.

### Power and motors

To power the NEMA 17 stepper motors I've converted an old ATX PC power supply and used the 12V output. The type of stepper motors I use for the Y- and Z axis are: 17HS19-2004S1, the type for the X axis is: 42BYGHW811. For the wiring I've used CAT5 network cable.

### Software that I mostly use to generate and send GCode:

* bCNC (https://github.com/vlachoudis/bCNC)
* Universal Gcode Sender (https://github.com/winder/Universal-G-Code-Sender)
* Easel by Inventables (http://easel.inventables.com)
* Fusion 360 with CAM (https://www.autodesk.com/products/fusion-360/students-teachers-educators)

### Help me make more stuff!

All my designs are free to use! If you want to support my work you can buy me a coffee at https://www.buymeacoffee.com/beukel Thanks!


