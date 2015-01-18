# GNSS-spoofing-detection
*GNSS Spoofing detection System*

This Open Source project about detection of «spoofing» GPS and GLONASS  signals which can be recieved by GPS/GLONASS simulators. 
#What need to start
I need NMEA data dump of GPS/GLONASS receiver which receive signals from GLONASS or GPS simulator.

In this NMEA logs must be include $GPGSV strings. Because I analyze levels of satellites signal and try to detect «spoofing».

If investigations with experemental NMEA data will be pasted, the project will have future.

So I`am interesting in community help.
#Algoritm
> Algoritm is build on some tests:
> 
>  1. Detect high Level of statelities signal level (C/N0).
>  2. Detect high level of signal Doppler offset.
>  3. Compare integrated Sensors values with recieved GPS/GLONASS Signal.  For example: 
> - speed sensors
> - move sensors
> - CAN bus

**Something else can be found through experience or to offer the community**

#Software implementation
C language.

#Related works
> - Andrew J. Kerns «[Unmanned Aircraft Capture and Control via GPS Spoofing]»

> - Aleksandar Jovanovic, Cyril Botteron, Pierre-Andre Fariné «[Multi-test Detection and Protection Algorithm Against Spoofing Attacks on GNSS Receivers]»

[Unmanned Aircraft Capture and Control via GPS Spoofing]: http://radionavlab.ae.utexas.edu/images/stories/files/papers/unmannedCapture.pdf
[Multi-test Detection and Protection Algorithm Against Spoofing Attacks on GNSS Receivers]: http://infoscience.epfl.ch/record/199530/files/ION_PLANS2014_AJovanovic_Published.pdf
 

