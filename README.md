# IoT_Photoresistor-LDR_using_Arduino

Light-dependent resistors (also known as photoresistors, photocells, or LDRs) are sensors that decrease their resistance as the amount of light that they’re exposed to increases. Essentially, the LEDs will get brighter as it gets darker around it and vice versa.

In this project, we are going to build a light sensor with an Arduino. The photoresistor will be connected to the Arduino’s analog input, allowing you to read the value with the analogRead() function. The LED will turn on and off based on the value read by the Arduino. PIN 9 will be set by the program to HIGH or LOW in order to turn the LEDs on and off. The threshold value for turning the LEDs on and off is 10. If the analog value is less than 10, the Arduino will turn the LEDs on. If the analog value is greater than 10, then the LEDs will turn off.
