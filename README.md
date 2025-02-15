# Simple-Motorola-Radio-Programming-Interface
A simple Motorola radio programming interface using the Pollin RS232-TTL converter kit and the addition of 1 diode.

The Pollin RS232-TTL converter can also be used to implement one of the many simple RIB-less programming interfaces for Motorola radios. All it takes is the addition of a single diode that you'll likely already have in your box of parts.

In the meantime, this kit has gone out of production but schematics for this kit are attached as a PDF file above. It can very easily be reproduced on a breadboard.

View the attached image file to see where to insert the diode. If you don't want to dedicate the interface to radio programming, the diode can just simply be screwed into the binding posts for TXD and RXD. The CTS and RTS are not used and left unconnected.

"Masse" on the circuit board is connected to the 5V supply's ground as well as the radio's programming ground.<br>
"RXD" on the circuit board is connected to your radio's programming interface pin. (Typically labeled BUS+ or SCI+).

I use this device for programming Motorola Radius GM300 mobiles as well as GP300 and P110 handhelds.
