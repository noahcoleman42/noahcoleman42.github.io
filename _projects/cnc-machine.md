---
title: "Senior Design Project - CNC Milling Machine"
excerpt: "Computer Numerically Controlled machine built using 3D printed parts that can carve wood and aluminum<br/><img src='/images/cnc-1.jpg' alt='cnc machine' width='980' height='736'>"
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
We spent the first week determining the major components of the project. During this time, we drew sketches and decided what the end product would look like, which parts we would design to be 3D printed, and which would be purchased. Each week, we came together as a team to determine what would be best to work on next, and split the workload according to team member preferences. I wanted to learn how to make 3D models, so I modeled most of the parts. We based the models off of our sketches, and used Fusion 360 to turn the pen and paper designs into 3D models. The models were printed on Prusa machines with infill percentages between 20 and 30 percent depending on the part. 

Unfortunately, just after printing the final part, the school shut down due to COVID-19, and our group had to finish assembling the machine outside of the lab. We no longer had a good place to work on the project as a group, so I took the machine to my hometown to finish assembling it. After testing movement control of the spindle carrier, the final step before attaching a 500 Watt, 12,000 rpm tree carcass shaper to it was adding safety protection. This was assembled using plexiglass sheets epoxied together to create a shield between users and the cutting tool. The images below show the progress made to the machine.

<img src='/images/base-complete.jpg' alt='machine base complete'>

<img src='/images/side-printed.jpg' alt='3D printed part laying on print bed'>

<img src='/images/spindle-holder-printed.jpg' alt='3D printed part laying on print bed'>

<img src='/images/carrier-complete.jpg' alt='mostly finished machine'>

<img src='/images/t-nuts.jpg' alt='plywood machine base with holes for attaching parts and wasteboard'>

<img src='/images/wasteboard.jpg' alt='Wasteboard attached to machine plywood base'>

<img src='/images/cnc-drawing-test1.jpg' alt='machine fails to draw spirals and decides to draw lines instead'>

<img src='/images/cnc-drawing-test2.jpg' alt='machine writes the letters s e n in progress of writting senior design flaw'>

<img src='/images/protective-shield.jpg' alt='plexiglass box missing top and bottom standing on a side to let epoxy dry'>

<img src='/images/cnc-done.jpg' alt='fully-assembled machine'>


Results
------
<img src='/images/manc-ave1.jpg' alt='sign with wood burrs around letters'>

<img src='/images/manc-ave2.jpg' alt='manc ave sign with letters painted black'>

<img src='/images/manc-ave3.jpg' alt='wooden sign with charred edges around letters'>



Teammates: <a href="https://www.linkedin.com/in/robert-tronnier-2ba4a5172/">Robert Tronnier</a>, <a href="https://www.linkedin.com/in/devin-kohnke-048b6b159/">Devin Kohnke</a>
