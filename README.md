# Environment-Mapping-Using-MATLAB21
This project shows how to use MATLAB (19 or later versions),
to map your surroundings using 
1) Arduino Uno
2) HC-SR04 Ultrasonic Sensor
3) Servo Motor

Install the MATLAB® Support Package for Arduino® Hardware before you can connect to your Arduino hardware from MATLAB.

**For versions R2018b or earlier, you will require to install the HC-SR04 addon-library

NOTE: If you are using MATLAB version R2019a or beyond,
 the Ultrasonic library is already integrated with the support package and you can directly use the ultrasonic constructor to create Ultrasonic object - 

>> **u = ultrasonic(a, 'D12', 'D13'); % for R2019a or beyond.
