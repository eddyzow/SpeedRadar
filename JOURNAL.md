*Total hours spent: 2* | *Date started: 18 June 2025*

---
# SpeedRadar
_life goes brrrrrrrrr and we need a way to measure its speed_

## entry #0 -- 6/19

so... i've finished four highway projects so far. and you know what I realized? none of the stuff i've built so far is actually useful to anyone else except me. two keyboards, a scooter, and a pomodoro timer. but recently an absolutely CRAZY idea came across my head. what's something that other people could see that I built just by driving across my house? well, the solution is here.

SpeedRadar is more than just a "radar." it's a LiDAR-based device, probably powered by an ESP32 or raspberry pi, that is positioned at an angle to the road near my house. the LiDAR takes rapid measurements of how far away the nearest object in its line of sight. it will know a car is approaching when the distance begins to decrease. when this happens, the LiDAR calculates the speed using some simple trig (r cosine theta!) and sends it wirelessly (or wired, i haven't decided yet) to a custom-made traffic sign that has a 64x64 LED matrix mounted on it, all attached to a tree for visibility. and thus the driver will get to know how fast they're going. as a bonus, if the driver is speeding (at least 40 mph) it will say SLOW DOWN and flash in red!!

most commercial companies produce these types of systems for over SIX THOUSAND DOLLARS!!!! i'm going to do it for less than the budget of an advanced highway project ($350).

i spent the past day and especially the past hour or so reseraching different types of LiDAR sensors and how effective they would be on the side of the road. i think i'll either use a pololu sensor (worked great on robotics projects in the past) or a special dedicated sensor. right now though i'm leaning towards that dedicated sensor since it has a reported 8 meter range!! i also went to various traffic sign companies to look for signs and brainstormed how i'm going to power this thing since my driveway is like 100 feet away from my house (probably a big battery? maybe i'll just scavenge my scooter battery). part of me thinks that this project is more expensive than it is complex but then again maybe it's just the SCALE of the project that makes it complex. this is easily the biggest thing i've ever made.

_time spent during session: 2 hours_
