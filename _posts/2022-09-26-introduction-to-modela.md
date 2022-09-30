---
layout: post
title: "Introduction to Modela"
subtitle: ""
date: 2022-09-26
background: '/PATH_TO_IMAGE'
---
 Introduction PCBs (Printed Circuit Board)

Chips


Programmer
a device that automatically controls the operation of something in accordance with a prescribed program.

Bootloading
A boot loader, also called a boot manager, is a small program that places the operating system (OS) of a computer into memory.

USB serial


Introduction to Modela machine:

At the fablab we use the: Modela MDX-20 3D milling machine
The instructions below are for copper and paper plates only and not copper to copper or glass. 

There are three important things to prepare in the machine before working with the software:


**TO THE MACHINE**


**Command buttons**: 
You can switch on and the machine
You can look at your piece, by bringing it close to the edge of the machine
You can bring the the drill up and down


**Layers of the machine**:


There are 4 layers on the plate:


1) Plastic see trough plate (acryllic material)

2) Acrylic plate (white color)

3) Sacrificial layer (that is also made of copper in case we drill to deep)

4) Copper plate

**It is important before we use our copper plate to measure it's thickness precisely with the help of a caliper**

You can fasten and unfasten the layers with the screw on the side.

We always position the layers on the left bottom corner

**Drill and bits**:


At the fablab we use two milling bits


0.4: for the interior and details


0.8: to cut the final product out


You take out and adjust the bit as shown below


Attention do not let the bit drop they will break easily, always use you your hand below!!




**TO THE COMPUTER**


As a first note, there is a certain flow on how we mill our design. We always go from interior to exterior and from thinner milling bit to thicker milling bit.

Attention when connecting the computer it shouldn't be on VIEW mode


open: Terminal


Type: Mods


Press: Enter


**In Mods**:


click on the left corner 


Click: Programs


Click: Open programs


Machine, Click: MDX mill-> PCB


go to: Websocket serial and click: close socket, close port

go on: next to Websocket pyserial and click: close socket, close port

AND then to Websocket serial and click: open socket, open port


go to Read png and click on: select png and choose your 
IMPORTANT: part to keep White, part to go Black

Set your DPI to 1000


go to Mill raster 2D:
 and then press: Calculate
 it will show you your design or press view to check it out.

 go to threshold:
 fill it to 0,5

 go to Roland MDX/imodela
 and you can manipulate the x and y axis via the computer and z axis via the machine
 example: if you have already some millings on your plate and you want to finish some of them , you do by adding in x or y some extra numbers to your choice and press: move to origin

 under jobsettings:
 fill in cut speed: 4
 jog: 2 (redline path jumping indications) 


**BACK TO THE MACHINE**


you can adjust the z axis by pressing the buttons UP and DOWN, after adgusting it to it's proper height as shown below, you can adjust the bit: loosen up caterfully with the torx wrench until the bit touches the plate, fasten it again you're ready to start

Go to: Websocket serial 
Press: send file

when finished do not forget to vacuum the plate

**FOR THE OUTLINE**


Change the milling bit as decripted above we need a 0.8bit now

Move the mill to the origin and level the z-axis

Select your new file again, again DPI: 1000

Go to: mill raster 2D

Set tool diameter: 0.8

Set cut depth: 0.6mm and max depth the the plates thickness that you calculated in the beginning.

Press : calculate

Press: view and check your file

the rest you can leave them with the same numbers as the previous milling.

Go to: Websoscket serial


Press: send file 

Again do not forget to vacuum the plate



**TO PAUSE THE PROCESS**


go to the machine at the command buttons and press: VIEW


**TO STOP THE PROCESS**


Press: VIEW


Press: UP and DOWN buttons at the same time


Press: move home and stop


**WHEN FINISHED**


Press: VIEW

vacuum the area

extract your piece with the spatula carefully not to snap the copper


clean your compartments with tweezers and a scalpel if needed


