# GNSS-spoofing-detection
GNSS Spoofing detection System

This Open Source project about detection of «spoofing» GPS and GLONASS  signals which can be recieved by GPS/GLONASS simulators. 
#What need to start
I need NMEA data dump of GPS/GLONASS receiver which receive signals from GLONASS or GPS simulator.

In this NMEA logs must be include $GPGSV strings. Because I analyze levels of satellites signal and try to detect «spoofing».

So I`am interesting in community help.
#Algoritm
Algoritm is build on some tests:

1. Detect high Level of statelities signal level (C/N0).

2. Detect high level of signal Doppler offset.

3. Compare integrated Sensors values with recieved GPS/GLONASS Signal. For example: speed sensors, move sensors and so on.

4. May be something else wil be find during expirements or .

