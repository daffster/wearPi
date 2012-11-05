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
