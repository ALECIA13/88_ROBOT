#Authors
Hlungwani Khanyisa (hlnkha010@myuct.ac.za)
Nyangiwe Someleze (nynsom001@myuct.ac.za)

##PROJECT OBJECTIVE

This is a project for a micro-mouse which is required to detect obstacles in its path. The system is made of four models: Power, Sensor, Motherboard and Processor. The power modules provides power to the whole system. The sensing system behaves like the eyes of the micro-mouse robot to detect the presence of an obstacle in its path. It uses infrared light for obstacle detection. It consists of two circuits, a receiver and an emitter circuit. The emitter circuit emits infrared light in the direction of an obstacle. The receiver circuit detects the emitted light and the output is taken from the receiver and connected to the processor. The processor controls LEDs which indicate obstacle detection. LED ON, means an obstacle is present. LED OFF, means no obstacle present. 

##HOW THE MODULES INTERFACE
The Power module has a connector which interfaces with the motherboard. Similarly with the Sensor module. The output of the Sensor Module transmits data to the Processor and the processor also sends PWM signal to the sensor. 

##STEP BY STEP GUIDE
This repository consists of the datasheets and KiCAD files used for both the Power and Sensor modules.
Connect all the Modules to the Motherboard.
Connect the Sensor Module to the Processor.

##EXPECTED RESULTS
The Processor controls the LEDs to indicate obstacle detection. 


