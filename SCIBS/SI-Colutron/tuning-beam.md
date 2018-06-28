# Tuning Ion Beam

* Move the Faraday cup so that is in the beam path and connected to the Keithley 617 programmable electrometer for instantaneous current readings. 
* Turn the rightmost knob of Floating High Voltage Supply so that “V-Accel” is selected. Then use the “V-Accel” knob (top left) to adjust to the desired voltage (Note: this will determine the beam energy, e.g. V-Accel = 1,000 V → 1 keV ion beam)
* Turn the rightmost knob of Floating High Voltage Supply so that “VF 1” is selected. Then use the “VF 1” knob (top right) to tune the beam in order to maximize beam current. Rule of thumb: VF 1 ≈ 0.75*V-Accel to maximize beam current, e.g. for V-Accel = 1,000 V, VF 1 will probably be around 750 V.
* Use course and fine adjustment knobs (typically fine adjustment only) under “El. Field” in Velocity Filter to adjust the horizontal deflection and maximize the current.
* Use course and fine adjustment knobs (typically fine adjustment only) under “Initial” in Beam Deflectors to adjust the vertical deflection and maximize the current.
    * Note: Can flip the switch beside the power switch to change the polarity
* Repeat steps to readjust “VF 1”, horizontal deflection, and vertical deflection until there is essentially no further increase in beam current

## Extra notes:
* Occasionally the supply for V-Accel and VF1 will drift, then the displayed voltages are not the actual voltages on the source.  Use HV-probe to verify that the voltages applied are the ones intended (Mostly important for V-Accel, as VF1 is just a focusing lens)
* Reference previous experiments with the same source to see if beam currents are appropriate, but keep in mind that beam current will continually decrease over the life of the source.
* Decreasing the beam current (at a given energy) to various percentages of the maximum after completing tuning (can most easily be achieved by adjusting “VF 1”.)
