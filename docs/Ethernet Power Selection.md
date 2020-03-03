Ethernet Power Selection 
-------------------------

>   There are no jumpers required to set which conductors provide power. The
>   unit contains two separate power paths for pairs 1,2 / 3,6 and 4,5 / 7,8.
>   These have the standard full wave bridge, so any polarity is accepted. The
>   voltage measurement function handles either polarity and can be used to
>   validate the expected polarity of the PSE port.

>   Note that this manual follows the industry standard terminology of referring
>   to a power pair (four wires) as a “pair”. The wire-to-pair mapping is:

| **Power Pair** | **Physical Wires** |
|----------------|--------------------|
| Main           | 1, 2 and 3, 6      |
| Alt            | 4, 5 and 7, 8      |

>   Note that the “Cisco” standard 1,2 = negative and 3,6 = positive is reported
>   as a positive voltage (main pair). Alt pairs with 4,5 = positive, and 7,8 =
>   negative is reported as a positive voltage.
