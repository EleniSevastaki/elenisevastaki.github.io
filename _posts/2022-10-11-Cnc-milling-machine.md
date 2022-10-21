---
layout: post
title: "CNC milling"
subtitle: ""
date: 2022-10-11
background: '/PATH_TO_IMAGE'
---

**IMPORTANT SAFETY MEASURES**

Materials danger:

We use screws to fasten our material on the sacrificial layer if the screw touches the screw while rotating it will create sparkles and in combination with the wood chips absorbed by the ventilation FIRE will occur

Wrong dimensions:

When choosing your milling bit, you should always use the same measument system for the other components and also in the computer.
At the fablab we use the metric system. 

Bit loose adjustment:

In combination with the above comment, a bit not well fastened can move and rotate or get loose, which will destroy your material but also eventually move on the wrong trajectory.

Speed: 

The bit moves with 18000 rotations per minute and it is very very DANGEROUS, always wear your hair up on a bun, wear safety glasses for any flyouts and wear protection when the machine is running.

Space organization:

Even if all the precaustions are taken, there could be dangerous materials in room. Pieces of wood on the way, full bag in the ventilation room, or even cups and liquids around the desks. Always evacuate any potential dangerous item before starting with the machine.

**NEVER EVER LEAVE THE MACHINE UNSUPERVISED WHEN IT'S ON**

**MACHINE DATA**

The fablab is using a Shopbot machine

Shopbot software runs Shopbot CNC tools

VCARVE software provides a powerful but intuitive software solution for creating and cutting parts on a CNC Router. (based on website description)

the maximum dimensions for milling are 1,22m x 2,44m

**MACHINE COMPONENTS**

Varis-speed
(Photo)

Ventilation buttons
(Photo)

Ventilation room
(Photo)

Ventilation switch in corner of the room
(Photo)

Ventilation at last buttons
(Photo)

Turn on-off switch
(Photo)

Emergency shut down button
(Photo)

**GENERAL LAYOUT OF THE MACHINE**
(photo)

**MACHINE PREPARATION**

                       Preparing your machine

1) Clean table by vaccuming it in case there are residues from the previous user

                       Preparing your material

2) Measure the thickness of your material with a caliper from different angles

3) Measure your milling of choice again with a caliper

4) Sand the sacrificial layer and check on the side if anything is bulging out.

5) Vacuum again the surface

6) Check your material expecially if it's a recycled one for any screws and abnormalities 

**MILLING BITS** 

Collet: is essentially what holds the tool bit in place within the CNC Router and therefore is an integral part of machining

Nut: Collet chuck nuts are threaded fasteners that secure collets to collet chucks

Bit: CNC router bits are the cutting implement at the end of the spindle on a CNC router. 

(Photo)

 Flutes: Flutes are the sharp slots that corkscrew upwards along the length of a milling bit. They are responsible for doing the cutting work when the bit is spinning. Bits come with 2, 3, or 4 flutes. A bit with more flutes has more cutting edges and consequently cuts faster and smoother than a bit with fewer flutes.
 
 End of the bit: 
 
 Ball nose(photo)
 End mill(photo)

Changing the milling bit:

Via the software Shopbot, you can control the x, y and z

Go on command

Press-> K

With the arrows you can control the x and y axis
with Page up and Page down you can control the z axis
and with CTRL+ Key (of your choice) you can go quicker

Bring your router close to you and level up the z axis

on the back of the skirt loosen up the Butterfly nut and remove the skirt (photo)

Check the direction of the screw

unlock the black wrench from the on switch

position the black wrench under and silver wrench above

Now with with a rotating opposite motion loosen up the screw
(Photo)

dismantle the bit, nut and collet add your new collet and bit
(Photo)

Fasten the the collet in the nut and the bit in the collet
attention do insert the bit deep enough.
(Photo)

Fasten the router with wrenches

Fix the skirt back

**Vcarve software**

A) Prepare your file : The files suppoted by Vcarve are

After Vcarve your file will be a crv

B) Open your new file on Vcarve

C) Job Setup
(Photo)

Drawing- fillet

D) TOOLPATH
(Photo)

1.Drilling toolpath (Photo)

Cutting depth: start depth-> 0.0mm and cut depth-> 3.0mm

Tool: Select tool (your milling bit) from tool database in the tool list of fablab amsterdam, choose your tool type and required parameters.

Edit tool: (photo)

Cutting parameters-> 

pass depth 

stepover (stepover explanation sketch)

Feed & Speed-> 

spindle speed: is  the rotation speed

feed rate: moment speed

plunge rate: how fast the bit is going in

tool number: 1 (cause only one milling bit is used)

CLICK-> APPLY
CLICK-> CALCULATE and the close

2.Pocket toolpath (Photo)

The priority in toolpaths goes from Drilling-Pockets-Inner Contours-Outer Contours

-Raster
(Photo)

-Offset
(Photo)

CLICK-> CALCULATE

3.Profile toolpath

-inner profiles
(Photo)

-outer profiles
(Photo)

E) Save your toolpath in two or different files one for the drilling, one for your design.

F) for shopbot your file

CLICK->CALCULATE

**Shopbot software**


**Fasten your material**

Depending on your material size and thickness you will need to screw your material on the sacrificial layer.

You should always note down the ammount of screws that are on the material to remember to take them ALL out after the carving process.

a) If the material is too small

Secure your material with screws first, then go to Vcarve and create a toolpath for your drilling and another for your design. 

(Photo)

B) If the material is big enough

When making your toolpath for your design, add another toolpath for your screws, stop the process and drill your screws and then continue.

(Photo)

Type of screws: we use Woodies a type of screws that do not brake easily for the millings convinience.

**AXES**

Click-> XY
Press ->K
Click-> (Z) Zero
Click Z [2 ] 

For Z axis
Press K
Move axis to clear point with keys
Press-> Z
Safety measures-> OK

press-> space bar to pause


**STARTING WITH THE MACHINE**

Starting the job

**AFTER YOU FINISHED WITH YOUR JOB**
