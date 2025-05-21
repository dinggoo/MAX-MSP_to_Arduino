# CMD Breda MAX-MSP-to-Arduino
By Mark Meeuwenoord 2025

Basic info version may 2025 


Arduino to Max module (main Max patch, source and arduino code)

(baudrate is set to 115200) If you have connection problems while using multiple IO try changing arduino code IO)
Sensor readout is set to 50ms (if you need faster readout send a message <pollspeed 20> to the serial to change the speed)

On the topside of the module you have data inlets to write to Arduino
On the bottom there data outlets. Here we read from the arduino (use the ON buttons to enable individual ports)

!!!!!!!!!!!!!!!!FIRST: Upload the Arduino_Max_Module_V2025.ino sketch to your arduino IT WILL NOT REALLY WORK WITH OTHER ARDUINO CODE!!!!!!!!!

1. Press the 'SYSTEM ON / OFF' in module. If no connection is established the menu on the right will say "no arduino connected". A good connection will show you the serial port your arduino is connected to.

2. Enable analog and / or digtal READOUT or both and then individual pins (keep this OFF if you are only writing to arduino)

3. You can switch the function of data inlets 3, 5, 6, 9 ,10 & 11 on the topside of the module to be digital, analog or servo mode (default = digital. (Note: you can connect multiple servo motors but HAVE TO USE A EXTERNAL POWERSOURCE