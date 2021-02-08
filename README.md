# UVic_FSAE_Throttle

This project is for UVic's FSAE electric team.

As of 2021-01-28, this program take input data from a linear position sensor (the throttle pedal),
converts the input to a percentage-activated,
then applies a throttle-mapping algorithm.
Finally, a requested torque value is outputted.

Currently, the throttle-map algorithm is naive and doesn't take into account the velocity of the vehicle.

UVic_FSAE_Throttle.ioc is the pinout.
UVic_FSAE_Throttle/core/src/main.c is the code.
