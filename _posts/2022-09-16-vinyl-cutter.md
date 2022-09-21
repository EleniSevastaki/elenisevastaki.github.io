---
layout: post
title: "Vinyl cutter"
subtitle: ""
date: 2022-09-16
background: '/PATH_TO_IMAGE'
---
Welcome to an introdcuction to vinyl cutting!


Let's begin with your design:

Depending on your software of choice make sure to save your file in black and white and the white area is the removable area, hence the black one the design of your final product. Then, save your file as an **SVG** file. 


In fablab we use the **CAMM-1 GX-24 Roland** vinyl cutter, already connected to the pc which uses **Ubuntu**. Next step is to open **terminal** a text based interface where you can command, manipulate files and execute programs.Start by typing :**cd mods** then **bash mods** and **enter**.
 

In mods **right click**on the module 


click on **open programs**


click on **machines** under **GX-GS 24 Vinyl Cutter** press **CUT**


Let's move to the machine now:
Open the machine with the switch on button. Start by adjusting the wheels under the white stripes shown as below:

Choose the roller or piece of your choice go to th back of the machine and put the **handle down** and insert the material from behind under the wheels adjust again the wheels if needed and press the **handle up**

Attention!! if you are using a normal vinyl the sticker should face up if your using a thermal sticker the sticker should face down.

Last choose for sheet: roll or piece depending on your sizing


Back to your PC in mods:

select your SVG file

Attention!! again your removable area is the white one
if not you'll have to fix it as below

**Inscape** 
-Open you file in inscape software
-Adjsust margins click: 
-Resize page to drawing selective (settings)
-Margins add 2
-Extession color: engative 
-Check size


**threshold** -> 0.9


**device server** and **print server** -> close sockets


after **re-open** sockets on **device server**


Go to Roland GX/GS 24 and add **force**->65 **speed**->1 
Recommended speed below:


**cut raster**->calculate


**vectorize, orient edge and edge detect** check them out 


**websocket device**-> send  files to device


AND IT'S STARTING


at the end take a your piece out,put the **handle down** cut the extra edges and your sticker is ready.




