# Expobar-Brewtus-PID-Shot-Timer
This project was done to add an automatic shot timer function to my Expobar Brewtus III. There are other ways of doing this with addon aftermarket timers but I wanted something more integrated into the machine.

Gicar is the manufacturer of most PID units for espresso machines, invluding the ones mounted in the Expobar Brewtus, ECM Technica/Mechanica/Classika, Izzo Alex Duetto etc.
The PID unit in the Expobar is very basic and outdated while the units for ECM and Izzo are more updated with added functions such as Eco-mode and Shot-timer.
They all share the same geometry and can easily be swapped for one another. Keep in mind that the Expobar PID is powered by mains voltage, while the ECM syncronika for example is powered by 24VDC and will not work for this application.

I used the PID from an ECM Technica IV which had a pleasing from panel design as well.

One major difference between the original Expobar PID and the newer units is the switching circuit. The Expobar switches incoming 110/230VAC to the SSR while the newer versions switches it's internal power supply of 6VDC. So you need to buy a compatible SSR and hook it up to +/- from the PID.

You also need the Gicar Optoboard and Opto/PID cable.
You can purchase the Opto/lever wires but those could also be made custom. Just make sure the wire insulation can handle high temperatures.

This was done to an Expobar Brewtus, but will work for any other espresso machine with a mains brew switch and a Gicar PID unit
