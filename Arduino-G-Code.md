
**Arduino G Code**

The following code will allow you to control speed and microstepping of your NEMA 17 stepper motor. While this code is meant to extrude the syringe only, a quick counterclockwise digitalWrite command can be added for bidirectional spinning motion. To change the speed, edit line 3 "const int stepsPerRevolution = x;. Microsteps can also be edited in the last section of the code for smoother revolutions.

![G Code](/Arduino-Code.jpg)
