*Total hours spent: 1* | *Date started: 18 June 2025*

---
# SpeedRadar
_life goes brrrrrrrrr and we need a way to measure its speed_

so... i've finished four projects so far. and you know what I realized? none of the stuff i've built so far is actually useful to anyone else except me. two keyboards, a scooter, and a pomodoro timer. but recently an absolutely CRAZY idea came across my head. what's something that other people could see that I built just by driving across my house? well, the solution is here.

SpeedRadar is more than just a "radar." it's a LiDAR-based device, probably powered by an ESP32 or raspberry pi, that is positioned at an angle to the road near my house. the LiDAR takes rapid measurements of how far away the nearest object in its line of sight. it will know a car is approaching when the distance begins to decrease. when this happens, the LiDAR calculates the speed using some simple trig (r cosine theta!) and sends it wirelessly (or wired, i haven't decided yet) to a custom-made traffic sign that has a 64x64 LED matrix mounted on it, all attached to a tree for visibility. and thus the driver will get to know how fast they're going. as a bonus, if the driver is speeding (at least 40 mph) it will say SLOW DOWN and flash in red!!

most commercial companies produce these types of systems for over SIX THOUSAND DOLLARS!!!! i'm going to do it for less than the budget of an advanced highway project ($350).

_time spent during session: 1_
