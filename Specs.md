**Calulating Resolution**

Known Constants | Measurements
--------------- | ----------------
Total Syringe Volume | 20 mL
Syringe Internal Ø | 19 mm
Threaded Rod Travel | 1.25 mm/ Rotation
Total Steps | 200 steps/ Rotation

![Minimum Resolution and Microstepping](/Resolution.jpg)

**Calculating Flow Rate**

![Flow Rate](/Flow_Rate.jpg)

**Limiting Factors**

The biggest limiting factor of the system sits heavily on the Arduino Uno microcontroller. With embedded systems comes processing speeds much less than your typical desktop. The Arduino Uno runs at a clock speed of 16 MHz and only 2 KB of SRAM (static random access memory). What this means is that the microcontroller can execute up to 16 million commands per second. However, clock cycles are shared between all communications in the system. Since you can only run so many step commands per second, CPU cycles and memory optimization are crucial. This optimization is achieved in the calls of the code, especially surrounding the validations, safety checks, and serial comms. If you are struggling to optimize your code and out of memory, you can always switch to the Arduino Mega. While it also runs at a 16 MHz clock speed, the SRAM is significantly increased to 8 KB. 
