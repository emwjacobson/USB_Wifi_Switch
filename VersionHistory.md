# Version History

Eventually I want to set something up on GitHub for proper versioning, but until then I'll keep track here.

## v0.1

I received the PCBs from JLCPCB on 11/14/22 and assembled them on 11/15. Programming the top had was easy enough using a "doner" NodeMCU that is piggybacked off of for programming.

When attempting to use the mosfet to switch power on to the output I realized that I used the mosfet in a p-channel arrangement while using an n-channel mosfet. Doh. This problem should be fixed in v0.1.1

## v0.1.1

This is the "patch" to fix the problem with the n-channel mosfet. Still has yet to be panelized and ordered, but the KiCAD project is correct.

## v0.1.2

Once I assembled v0.1.1, I realized that I had the wiring for the Female USB swapped! In addition, the pin labels for the mosfet still reflected the p-channel orientation, which caused them to be swapped as well.

## v0.2.0

Redesigned layout to be a bit more optimized, as well as put the power monitering IC on the correct side of the USB plug.

## v0.2.1

Added place for resistor between D+ and D-
