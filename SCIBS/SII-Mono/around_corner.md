# Procedure for tuning a beam around the Mono

## Pre-Setup

-  Follow procedures for starting a beam in S1
-  Turn off the ion gauge for S2
-  Connect an electrometer to F and to FC2
-  Connect an electrometer or other similar device to M

## Supply turn on order:

1.  First turn on the HV supplies in the rack below S2
2.  Next turn on the controller supplies

Turn off in reverse order for turning on

## Step 1: Tune a beam on F

The FRED box has some BNC cables connected to it, each is labelled at the end, the one labelled "F" is the front entry plate of the Mono, so start by tuning the beam onto this part. This should involve adjusting the voltage VF1, the Wien filter voltage/current, as well as the vertical deflection voltage on the Colutron, most of this step involves only adjustments in S1

## Step 2: Tune Mono, and look for beam at FC2

Adjust the voltage on the mono for the required pass voltage, note that the voltage reported by V_accel in S1 might not be the same as the actual voltage applied, it can vary by 5-10%, so some adjustments might be needed of the initial beam turning to get a desired energy through the mono.

## Step 3: Locate hole in F

Locating the hole in F is done by adjusting the X1/Y1 deflector voltages, as well as adjusting the voltages on VF1 and VF2. generally the VF1 voltage will be about what it was when tuned, but minor adjustments might be needed. To determine the position of the hole, adjust X1/Y1 until a set of parameters is found where small adjustments in either direction, of either voltage, will result in an increase in current on F, also adjust VF2 such that the minimum voltage on F is as low as possible.

### Notes for locating the hole:

It helps to be monitoring the beam current on the other side of the Mono (at FC2 and M), as that should behave with an opposite trend from the current on F, when F's current drops, the current on the other side should rise.

If most of the beam is hitting M, but almost none on FC2, then do slight adjustments to the Mono's voltage, if the voltage does not very closely correspond to the pass energy of the velocity filter, then most of the beam will end up hitting M instead of passing through the exit aperture.

After adjusting VF2, the parameters in X1/Y1 will tend to shift a bit, so make fine adjustments to VF2, then re-adjust X1/Y1. similar for any adjustments to VF1.