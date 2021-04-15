# Procedure for Starting Ion Beam
**__SAFETY NOTE:__** 
Once acceleration voltage is turned up everything in the acrylic box is potentially at “beam potential”. Be cautious of HIGH VOLTAGES!

Use the switch on the Arduino to connect the bias batteries, there should be a red light on when this is connected, if computer control is being used instead, turn this switch off.

Note: Do not leave these batteries connected to the source for extended periods of time while not running the beam to avoid draining the batteries.

* Turn on the Floating High Voltage Supply (switch on the far left)
* Turn on the beam deflectors
* Leftmost switch under “Initial” in Beam Deflectors (vertical deflection)
* Leftmost switch under “El. Field” in Velocity Filter (horizontal deflection)
* Turn on “Filament” switch on the right side of the MIT Ion Source rack (be careful since switch is not seated properly).
* Make a note of pressure on channel 1 (active gauge in front of the source)
* Bringing up source current (MIT Ion Source):
    * For each step below note the time, initial current setting (i.e. before relaxation), and count number on knob. Also keep an eye on the pressure! In the event of a pressure spike let everything sit for a while before incrementing the source current.
    * Turn dial clockwise until current is ~0.5 A. Wait about 10 minutes for stabilization (waiting longer is not detrimental).
    * Turn dial clockwise until current is ~0.5 A higher than the final stabilized current from the previous step. Wait another 10+ minutes for stabilization.
    * Continue incrementing the current in this manner until desired current is reached (See ion sources for optimal currents)

## Troubleshooting – common issues:
* Use high voltage probe and DMM to measure voltage on the isolated part of the source in the acrylic box. (The display for “V-Accel” shows the programmed voltage and not a measured voltage.)
* Use DMM to measure the voltage across the three series 6V batteries (should be around 19V).
* Check that the bias battery voltage is being applied to the source, if not, ensure that the servo arm from the Arduino is properly positioned.

## Update the source log:
Record the time, source current, number of turns, and the pressure (S1) in the source log every time you start the beam (before and after turning up the source) and when you shut down the beam (before and after turning the source off).
