UUT Connections
---------------

>   The RT-PoE5 has 24 test ports, configured as 12 pairs (1-2, 3-4, 5-6, etc.).
>   Each port can act as a PD load to the UUT. Also, each port pair can be
>   configured to pass data from one port to the other via internal
>   straight-through connections, allowing the loads to be applied while passing
>   traffic. All data path connections are made via signal relays and 100 ohm
>   differential pairs for data integrity.

>   Connect the port of the PoE supplying device under test to the UUT connector
>   via a standard straight-through Ethernet connector (see the [Ethernet
>   Cables](#_Ethernet_Cables) section for more information regarding cables).
>   There is an 802.3bt class transformer isolating the UUT ports in each port
>   pair so that power can be tapped from the UUT (see the [Data
>   Path](#_Data_path) section for more details).

>   Note that the devices connected to any given port pair cannot "see" the
>   power from the other port. In other words, the UUT ports in a port pair are
>   connected from a data perspective, and each UUT port connects to the RT-PoE5
>   active load from a power (PoE) perspective.

>   *NOTE: with high power loads, the DC balance of the patch cables used is
>   important to avoid DC saturation of the Ethernet transformers. DC Balance
>   (DC resistance per side of the power-carrying pair) should be within 3%. The
>   standard patch cable specifications of Cat 5, 5e, and 6 do not specify DC
>   balance.*
