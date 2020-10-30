# Modifications made to HVM-2 in 2020-10 are below

HVM-2 has had some buffers/amplifiers inserted between the inputs and outputs from/to the Mono Controller supply. These have the following effects:

1.  There is now approximately a 20% amplificiation for the signals sent to/from the box
2.  The DC offset for the IO for HVM-2 can be adjusted by trimpots on the amplifiers

Due to 1. above, the feedback voltage was no longer in the adjustable range for the controller's display, so as a result, the feedback circuit has an additional trim pot afterwards as a voltage divider, this allows for adjusting the voltage on the display. Due to impedance effects, both this scaling trimpot, and the offset trimpot need to be adjusted simultaneously to achive the correct value on the display.

## Additional notes:

As of 2020-10-30, only the lower voltage feedback has had the trimpot added after the amplifier, and only this side has been tuned, if one is added for the 0-20k side, this should be updated accordingly.