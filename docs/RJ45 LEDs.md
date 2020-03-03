RJ45 LEDs
---------

>   Each RJ45 connector has a yellow LED and a green LED. The yellow LED will be
>   lit when the port is processing a command from the control card/operator,
>   and will be off otherwise.

>   The green LED will be lit according to the following table when the
>   “power-good” status of the IEEE controllers go active. The “status” command
>   can also be used to report the “power-good” status of each PoE PD
>   controller.

| Green LED State       | Definition                          |
|-----------------------|-------------------------------------|
| Off                   | Both power-good signals inactive.   |
| On solid              | Both power-good signals active.     |
| One blink per second  | Main pair power-good signal active. |
| Two blinks per second | Alt pair power-good signal active.  |

>   Note that when the loads are connected and the fans are running, the PoE5
>   will send an internal command to the ports to check the heatsink
>   temperature. This will cause the yellow LED to blink on a regular basis, and
>   is normal operation.
