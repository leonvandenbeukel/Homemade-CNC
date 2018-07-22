# Homemade CNC

## Warning!!

This machine is 'under construction' and will be modified over time. I share my design for others to experiment and learn from it. At the moment I would not even recommend creating this machine yourself :smiley:

### 2018/07/22 Update: 
I'm currently working on an improved version so my advise is not to build the current version. More info to come... 

### YouTube video

<a href="https://youtu.be/CDPI4gFxyAQ" target="_blank"><img src="https://img.youtube.com/vi/CDPI4gFxyAQ/0.jpg" 
alt="Click to view: Homemade CNC with 3D printed parts" width="500" border="1" /></a>

### Cost estimation

* [Link to Google Sheet](https://docs.google.com/spreadsheets/d/e/2PACX-1vRAYMiPSLNSFAx9bK11CHd6tc-5phIbJY1AtSAjcyATRbZvdDSyTKB5_P1hYdHO0VamVOjqQyz4cLyY/pubhtml?gid=0&single=true "Link to Google Sheet")

### About the video
The video is about making my homemade DIY CNC with 3D printed parts. I've designed the 3D printed parts with Fusion 360. 

To control the machine I'm using an Arduino UNO with GRBL firmware and an Arduino CNC Shield. There are plenty of tutorials to find on how to connect and use it so I did not show it in the video. Here are some useful links:

* [GRBL](https://github.com/gnea/grbl)
* [Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield/)

### Power and motors

To power the NEMA 17 stepper motors I've converted an old ATX PC power supply and used the 12V output. The type of stepper motors I use for the Y- and Z axis are: 17HS19-2004S1, the type for the X axis is: 42BYGHW811. For the wiring I've used CAT5 network cable.

### Software that I mostly use to generate and send GCode:

* bCNC (https://github.com/vlachoudis/bCNC)
* Universal Gcode Sender (https://github.com/winder/Universal-G...)
* Easel by Inventables (http://easel.inventables.com)
* Fusion 360 with CAM (https://www.autodesk.com/products/fus...)

### 3D Printing

The 3D printer I use is an Anet A8. The parts are printed with PLA, mostly 20% infill and 0.2 or 0.4 setting. Use higher infill for parts that must be stronger, for example the stepper motor mounts.

### Dimensions

Base front panel: 710 x 180 x 22 mm or 28" x 7" x 0.86"
Base side Y rails: 935 x 100 x 22 mm or 36.8" x 3.9" x 0.86"

X rails carriage side panel: 360 x 185 x 10 mm or 14.2" x 7.3" x 0.39"
X rails tube length: 630 mm or 24.8"

Z rails tube length: 200 mm or 7.9"

Wasteboard: 610 x 920 x 22 mm or 24" x 36.2" x 0.86"

The threaded rods for Y and X rails are 8 mm (0.31") stainless steel. Lengths can be cut afterwards to fit the frame. Aluminium tubes are 15 x 15 mm (0.59").
