# Mechanical Assembly for Syringe Pump

## Bill of Materials

Item         | Quantity
------------ | -------------
[Aluminum Extrusion (1ft)](https://www.mcmaster.com/47065T107/) | 1
[Threaded Linear Rod (300mm)](https://www.mcmaster.com/1078N32/) | 1
[Linear Rod (300mm)](https://www.mcmaster.com/6112K44/) | 1
[Linear Bearing (#61205K75)](https://www.mcmaster.com/61205K75/) | 1
[External Retaining Ring (#9968K32)](https://www.mcmaster.com/9968K32/) | 2
[M8 Hex Nut (1.25 mm thread)](https://www.mcmaster.com/90592A022/) | 1
[5/32" T Nut & Bolt (1/4"-20 thread)](https://www.mcmaster.com/47065T139/) | 6
[M3 screws (Depth 4.5mm)](https://www.mcmaster.com/screws/socket-head-screws/alloy-steel-socket-head-screws-8/) | 4


## Fusion 360 Model

<iframe src="https://vanderbilt428.autodesk360.com/shares/public/SH56a43QTfd62c1cd968fc7ec97f3bc74a30?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Mechanical Assembly Photos

![Mechanical Assembly of Syringe Pump](/syringe_specs.png)

### The entire Fusion 360 design is based on the specs of the syringe and NEMA 17 motor. Note that not all syringe brands have the same dimensions even if they hold the same capacity. 

![Mechanical Assembly of Syringe Pump](/Mech_Assembly_Pics/mech_assembly.jpg)

### The 3D printed stepper motor mount, plunger driver, syringe barrel holder, and syringe tip holder are aligned on the aluminum extrusion (in order). The stepper motor mount, barrel holder, and tip holder are anchored to the extrusion via T nuts and bolts (2 each). While the acme screw turns to drive forward motion at the defined flow rate in the G-code, the plunger driver moves with linear motion thus extruding the contents of the syringe. 



![Mechanical Assembly of Syringe Pump](/Mech_Assembly_Pics/mech_assembly_2.jpg)

### When designing the motor mount, make sure to obtain a snug fit in the gantry. This will allow the four M3 screws to be properly secured at a depth of 4.5mm to anchor the NEMA 17 motor in place. 



![Model 3D Components](/Mech_Assembly_Pics/mech_assembly_3.jpg)

### Designing the 3D parts and assembling the complete model in Fusion 360 isn't too difficult. Give yourself a bit more time to get the plunger driver right if you are new to the software as positioning of the M8 hex nut kind of sucks. Regardless, Fusion 360 is quite user friendly, and it seems to be the software many people are moving to, especially as the CNC extension for Solidworks was recently made obsolete. 
