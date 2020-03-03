Fans
----

>   The fans run at a minimum speed whenever the tester is on and the loads are
>   disconnected. This is required to exhaust the internally-generated heat.

>   The fans will also run at a minimum speed when the total load on any test
>   port is 100mA or less (‘set’ value), or 4W or less (‘pwr’ value), and the
>   load is connected (“conn 1”).

>   The fans will run at full speed when any of the test ports have a total load
>   greater than 100mA or 4W, and the load is connected. After all ports are no
>   longer connected (e.g. reset command has been issued) the fans will run at
>   full speed until the nominal heatsink temperature has been reached, at which
>   point the fans return to the minimum speed.
