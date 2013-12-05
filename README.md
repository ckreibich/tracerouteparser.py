tracerouteparser.py
===================

tracerouteparser.py is a Python module that implements a parser for traceroute output. It's not a traceroute implementation.

Features
--------

* Parses traceroute info into a series of hop objects, each consisting of one or more probe results, likewise object instances.
* String formatting produces familiar traceroute output.

Example
-------

The built-in demo parses a traceroute output string and prints the
stringification of the resulting data structures:

    $ python ./tracerouteparser.py
    traceroute to edgecastcdn.net (72.21.81.13)
     1  *  *
     2  *  *
     3  *  *
     4  10.251.11.32 (10.251.11.32) 3574.616 ms  0.153 ms
     5  10.251.10.2 (10.251.10.2) 465.821 ms  2500.031 ms
     6  172.18.68.206 (172.18.68.206) 170.197 ms  78.979 ms
     7  172.18.59.165 (172.18.59.165) 151.123 ms  525.177 ms
     8  172.18.59.170 (172.18.59.170) 150.909 ms  172.18.59.174 (172.18.59.174) 62.591 ms
     9  172.18.75.5 (172.18.75.5) 123.078 ms  68.847 ms
    10  12.91.11.5 (12.91.11.5) 79.834 ms  556.366 ms
    11  cr2.ptdor.ip.att.net (12.123.157.98) 245.606 ms  83.038 ms
    12  cr81.st0wa.ip.att.net (12.122.5.197) 80.078 ms  96.588 ms
    13  gar1.omhne.ip.att.net (12.122.82.17) 363.800 ms  12.122.111.9 (12.122.111.9) 72.113 ms
    14  206.111.7.89.ptr.us.xo.net (206.111.7.89) 188.965 ms  270.203 ms
    15  xe-0-6-0-5.r04.sttlwa01.us.ce.gin.ntt.net (129.250.196.230) 706.390 ms  ae-6.r21.sttlwa01.us.bb.gin.ntt.net (129.250.5.44) 118.042 ms
    16  xe-9-3-2-0.co1-96c-1b.ntwk.msn.net (207.46.47.85) 675.110 ms  72.21.81.13 (72.21.81.13) 82.306 ms

License
-------

tracerouteparser.py is using the standard [BSD license](http://opensource.org/licenses/BSD-2-Clause).
