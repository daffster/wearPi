wearPi
======

My attempt at building a wearable PC.

Components
==========

Hardware
--------
* Raspberry Pi
* MyVu Solo
* Android phone (Samsung Galaxy S2)
* Rechargable USB Battery pack
* Ti EZ430 Chronos (http://processors.wiki.ti.com/index.php/EZ430-Chronos)

Software
--------
* Linux on the Raspberry Pi
* Python
* X11 on the Pi

Concept
=======

MyVu Solo HMD modified to monocular, and mounted on a pair of glasses (or custom bracket) 
USB Battery to power the Raspberry Pi, and the built in "Pendant" battery to power the MyVu Solo
Composite video out from the Raspberry Pi to the (modified) MyVu Solo

App runs on the Android device, and publishes data (JSON? Maybe?) to an API running on the Raspberry Pi (Bluetooth? Wifi?), which in turn formats it to display on the HMD

User input can be taken from the EZ430 Chronos Watch. Also available on the watch are 3-Axis Accelerometer, Pressure Sensor and Temperature sensor. Possible also to connect watch to a heart rate monitor.

Progress
========
Stripping down the MyVu Solo to make a Monocular HMD http://daffy.za.net/2012/11/wearpi-hmd-1/

