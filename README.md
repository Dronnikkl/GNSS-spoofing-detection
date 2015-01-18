# GNSS-spoofing-detection
*GNSS Spoofing detection System*

This Open Source project about detection of «spoofing» GPS and GLONASS  signals which can be recieved by GPS/GLONASS simulators. 
#What need to start
I need NMEA data dump of GPS/GLONASS receiver which receive signals from GLONASS or GPS simulator.

In this NMEA logs must be include $GPGSV strings. Because I analyze levels of satellites signal and try to detect «spoofing».

http://stackoverflow.com/questions/28001975/where-i-can-get-nmea-data-dump-of-glonass-or-gps-simulator?noredirect=1#comment44408851_28001975

I have GPS Receiver, and have experience to dump NMEA from it, so I have Real signal. But i have not dumps of spoofed signal which my GPS receiver can get from GPS simulator which generate spoofed signals, so I can't make charts and software test. In one of related works discussed that if we have C/N0 values of spoofed signal we can detect spoofing. In NMEA specification C/N0 is SNR value of satellite. Maybe I can generate spoofed signal programatticaly, but I think it will not be a clean experiment.

If investigations with experemental NMEA data will be pasted, the project will have future.

So I`am interesting in community help.
#Algorithm
> Algorithm build on some tests:
> 
>  1. Detecting high level of statelities signal level (C/N0).
>  2. Detecting high level of signal Doppler offset.
>  3. Compare integrated Sensors values with recieved GPS/GLONASS Signal.  For example: 
> - speed sensors
> - move sensors
> - CAN bus
> - angle sensors

**Something else can be found through experience or to offer the community**

#Software implementation
C language.

#Related works
> - Andrew J. Kerns «[Unmanned Aircraft Capture and Control via GPS Spoofing]»

> - Aleksandar Jovanovic, Cyril Botteron, Pierre-Andre Fariné «[Multi-test Detection and Protection Algorithm Against Spoofing Attacks on GNSS Receivers]»

[Unmanned Aircraft Capture and Control via GPS Spoofing]: http://radionavlab.ae.utexas.edu/images/stories/files/papers/unmannedCapture.pdf
[Multi-test Detection and Protection Algorithm Against Spoofing Attacks on GNSS Receivers]: http://infoscience.epfl.ch/record/199530/files/ION_PLANS2014_AJovanovic_Published.pdf
 

