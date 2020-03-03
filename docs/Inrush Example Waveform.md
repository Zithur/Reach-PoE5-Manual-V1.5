Inrush Example Waveform
-----------------------

>   The example waveform below shows the current waveform for the main pair on a
>   single port during the inrush period. The voltage is supplied by a standard
>   bulk power supply set to 50v. The commands used for the setup are:

>   p1 set 500,0  
>   p1 conn 1,0

>   The initial rising edge occurs when the voltage goes above about 38v, and
>   this pulse is the bulk capacitor charging. Then the load transitions to the
>   100ma (approx.) minimum load for the duration of the inrush timer setting
>   ([INR](#_INR) command). When the inrush timer expires, the load goes to the
>   selected value of 500ma.

![](media/8033e48aecd5a6883ec1bf277bf3ea28.png)

>   InrushWaveform
