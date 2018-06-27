# Homemade CNC

### YouTube video

<a href="https://youtu.be/CDPI4gFxyAQ" target="_blank"><img src="https://img.youtube.com/vi/CDPI4gFxyAQ/0.jpg" 
alt="Homemade CNC with 3D printed parts" width="240" height="180" border="10" /></a>

### Cost estimation

[Link](https://docs.google.com/spreadsheets/d/e/2PACX-1vRAYMiPSLNSFAx9bK11CHd6tc-5phIbJY1AtSAjcyATRbZvdDSyTKB5_P1hYdHO0VamVOjqQyz4cLyY/pubhtml?gid=0&single=true "Link")

### About the video
The video is about making my homemade DIY CNC with 3D printed parts. I've designed the 3D printed parts with Fusion 360. 

To control the machine I'm using an Arduino UNO with GRBL firmware and an Arduino CNC Shield. There are plenty of tutorials to find on how to connect and use it so I did not show it in the video. Here are some useful links:

[GRBL](https://github.com/gnea/grbl)

[Arduino CNC Shield](https://blog.protoneer.co.nz/arduino-cnc-shield/)

### Power and motors

To power the NEMA 17 stepper motors I've converted an old ATX PC power supply and used the 12V output. The type of stepper motors I use for the Y- and Z axis are: 17HS19-2004S1, the type for the X axis is: 42BYGHW811. For the wiring I've used CAT5 network cable.

### Software that I mostly use to generate and send GCode:

* bCNC (https://github.com/vlachoudis/bCNC)
* Universal Gcode Sender (https://github.com/winder/Universal-G...)
* Easel by Inventables (http://easel.inventables.com)
* Fusion 360 with CAM (https://www.autodesk.com/products/fus...)

### Warning 

If you want to make this machine yourself: it's 'under construction' and will be modified over time. Please consider to subscribe to my YouTube channel if you want to see more updates and other projects that I do. 

### 3D Printing

The 3D printer I use is an Anet A8. The parts are printed with PLA, mostly 20% infill and 0.2 or 0.4 setting. Use higher infill for parts that must be stronger, for example the stepper motor mounts.

