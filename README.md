# Tire-Filler
Program to automate setting tire pressures using an Arduino(Nano).

I am an automotive technician by trade and setting tire pressures especially on new cars that are set high for transport seemed like a waste of time. Decided to build an automated system to set the pressures.

For this set up I used an Arduino Nano, 2 Groove relays, 2 3/8NPT solenoids running on 12V, a 12V Dewalt battery for the solenoids, Normal 3 position rocker switch, 9V battery for the Arduino (Found the spike from the solenoids turning on and off caused issues so used the 2 battery setup as a quick fix for now), a pressure sensor from an A/C system from a car, and displayed the info on a 16,2 LCD screen.

It was my first attempt at my own program for Arduino's and for sure needs some smoothing out but it works, and I no longer have to sit there and set the tire pressures manually so it is a win!

Edits and upgrades on the list for the future would be get it down to operate solely on the Dewalt battery and add a light set up to indicate whether the pressure is too low. If the tire is 5 PSI lower than set one color, 10 PSI lower than the set pressure to be set to another color and same for too high. Color to indicate pressure has been reached. This is so when you are doing something else while the machine does its thing I can see from a distance what is going on.
