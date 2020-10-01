---
title: GPS And Relativity
date: 05 Feb 2020
author: Janvi
description: Einstein's famous theory and Google Maps- more related than you might
  think.

---
_Special Relativity:_

1. Time dilation: According to this phenomenon, for an observer in an inertial frame of reference a clock moving comparable to the speed of light, relative to the observer will tick slower.
2. Length Contraction: According to this phenomenon, for an observer in an inertial frame of reference, the length of the object moving comparable to the speed of light, relative to the observer appears to be shorter along the dimension of motion.

_General Relativity:_  
According to this theory, the gravity of an object creates a curved manifold in the four-dimensional spacetime. Time is considered to be a separate dimension, similar to space and because of this, there will be a difference in time elapsed by two clocks at different potentials (distance for the earth in this case).

_How does satellite navigation system depend on understanding of general relativity?_  
There are 24 satellites in circular orbits with an orbital period of 12 hours, distributed in 6 orbital planes. Each satellite is provided with an atomic clock. These satellites are distributed such that at least 4 satellites are visible from any point on earth at any given instant.

Relativistic effects which are taken into account are due to:

![](/images/IMG-20200205-WA0007.jpg)

1. Different observed clock rates at different altitudes (general relativity)
2. Different observed rates of clocks in relative motion (special relativity)  
   When observed from the surface of earth, the clocks on the satellites appear to be running faster according to relativity. A calculation using General Relativity predicts that the clocks in each GPS satellite should get ahead of ground-based clocks by 45 microseconds per day. Special Relativity predicts that the on-board atomic clocks on the satellites should fall behind clocks on the ground by about 7 microseconds per day because of the slower ticking rate due to the time dilation effect of their relative motion.The combination of the two relativistic effects predicts that onboard satellite should tick faster than the clocks on the surface by 38 (45-7) microseconds.  
   If these effects were not properly taken into account, a navigational fix based on the GPS constellation would be false after only 2 minutes, and errors in global positions would continue to accumulate at a rate of about 10 kilometers each day!

_How are GPS signals encoded to allow precise triangulation?_  
Basically, 3 dimensions are needed to specify a location on earth, namely, east-west (longitude), North-south(latitude) and altitude. Therefore 3 overhead satellites are needed to specify a position on earth. Each satellite emits a signal encoding local time of emission and satellite’s position in global coordinates at the emission event. This position is continually revised using the data uploaded from control stations on the ground.

The local clock that is the handheld GPS receiver records the local time of reception of each signal, subtracts emission time ‘t’ (encoded with the incoming signal) to determine the lapse in t-coordinate and hence how far the signal has travelled at the speed of light in global that can be done precisely by triangulation (intersection of 3 spheres). Even a simple handheld GPS receiver can determine the position precisely up to and accuracy of 5-10 meters in only a few seconds.

_How accurate can GPS signal be made?_  
Using a hand-held GPS receiver which detects radio emissions from any of the satellites which happen to be overhead, users of even moderately priced devices can determine latitude, longitude and altitude to an accuracy which can currently reach 15 meters, and local time to 50 billionths of a second. Apart from the obvious military uses, GPS is finding applications in airplane navigation, oil exploration, wilderness recreation, bridge construction, sailing, and interstate trucking, to name just a few.

Reasons for reduced accuracy practically:  
1\.Ionospheric effects  
2\.Shifts in the satellite orbits  
3\.Clock errors of the satellites' clocks  
4\.Multipath effect  
5\.Tropospheric effects  
6\.Calculation and rounding errors

_References:  
http://www.astronomy.ohio-state.edu/  
http://www.physicscentral.com/  
Gravitation and Cosmology: Principles and Applications of general theory of relativity By Steven Weinberg  
Edwin F. Taylor, and John Archibald Wheeler. Exploring Black Holes: Introduction to General Relativity  
“GPS SYSTEMS LITERATURE: INACCURACY FACTORS AND EFFECTIVE SOLUTIONS” by Li Nyen Thin, Lau Ying Ting, Nor Adila Husna and Mohd Heikal Husin International Journal of Computer Networks & Communications (IJCNC) Vol.8, No.2, March 2016 DOI : 10.5121/ijcnc.2016.8211 123_

_- Janvi_