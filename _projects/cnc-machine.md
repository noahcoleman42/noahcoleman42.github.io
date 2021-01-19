---
title: "Senior Design Project - CNC Milling Machine"
excerpt: "Computer Numerically Controlled machine built using 3D printed parts that can carve wood and aluminum<br/><img src='/images/cnc-1.jpg' width='701' height='629' alt='fully-assembled machine'>"
collection: projects
---

What is a CNC machine?
------
A CNC machine is a machine that follows computer instructions to automate a tool's movements. 3D printing heads, laser cutters, and plasma cutters can all be computer numerically controlled (CNC), but generally, the term refers to machining tools like mills or lathes.

Why we built it
------
Since CNC machines are controlled by computers, they can reach levels of precision that only masters of a craft could obtain. As engineers, my teammates and I are far better at modeling objects on the computer than carving them with hand tools. Unfortunately, industrial CNC machines can cost thousands of dollars, which to hobbyist college students is completely unjustifiable. I have a saying for situations like this: if you can't afford it, you've gotta build it.

How it works
------
The machine uses stepper motors to control the movement of a high-speed spindle in all 3-axes (X, Y, Z). A computer speaks to the motor drivers (which "drive" the motors) in a language called G-code. G-code instructions tell the motor drivers how to move the motors, controlling their direction and speed. A computer-aided manufacturing (CAM) program (like the one built into Fusion 360) uses designer specified toolpaths to compile a list of instructions into a .gcode file. This file is read by a program called CNCjs which sends the G-code instructions to an Arduino running a firmware called GRBL, which outputs signals via the Arduino pins to control the motors.

CNCjs allows users to manually control the movement of the machine to match the starting location of your design's toolpath with the real world. The program also helpfully displays a real-time animation of the path via a graphical interface.

How we built it
------


Results
------


Teammates: <a href="https://www.linkedin.com/in/robert-tronnier-2ba4a5172/">Robert Tronnier</a>, <a href="https://www.linkedin.com/in/devin-kohnke-048b6b159/">Devin Kohnke</a>
