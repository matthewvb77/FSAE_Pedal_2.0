# FSAE_Pedal_2.0

This project is for UVic's FSAE electric team.

As of 2020-12-23, this program take input data from a linear position sensor (the throttle pedal),
converts the input to a percentage-activated,
then applys a throttle-map algorithm.

Finally, a value to be sent to the inverter is outputted.

FSAE_Pedal_2.0.ioc is the pinout
FSAE_Pedal_2.0/core/src/main.c is the code
