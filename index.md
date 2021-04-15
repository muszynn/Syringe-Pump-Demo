# How to Build a Syringe Pump

![Mechanical Assembly of Syringe Pump](/Syringe-Pump-Demo/Mech_Assembly_Pics/mech_assembly.jpg)

**Overview**


**See Mechanical Page** [here](/Syringe-Pump-Demo/Mechanical-Assembly)


**See Electrical Page** [here](/Syringe-Pump-Demo/Electrical-Assembly)


**See Arduino G-code Firmware** [here](/Syringe-Pump-Demo/Arduino-G-Code)


**See Flow Rate Specs** [here](/Syringe-Pump-Demo/Specs)


**Limiting Factors**

The biggest limiting factor of the system sits heavily on the Arduino Uno microcontroller. With embedded systems comes processing speeds much less than your typical desktop. The Arduino Uno runs at a clock speed of 16 MHz and only 2 KB of SRAM (static random access memory). What this means is that the microcontroller can execute up to 16 million commands per second. However, clock cycles are shared between all communications in the system. Since you can only run so many step commands per second, CPU cycles and memory optimization are crucial. This optimization is achieved in the calls of the code, especially surrounding the validations, safety checks, and serial comms. If you are struggling to optimize your code and out of memory, you can always switch to the Arduino Mega. While it also runs at a 16 MHz clock speed, the SRAM is significantly increased to 8 KB. 

