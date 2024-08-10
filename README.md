# Tapchanger

A toolchanger for Sovol SV08.

## Features
* Uses the Nozzle, planetary Extruder and Extruder Bord from the original Sovol SV08 Printhead.
* Off the shelf voron parts, except for bearings.
* Uses [Dragon Burner](https://github.com/chirpy2605/voron/tree/main/V0/Dragon_Burner) toolhead - can fit 6 hotends in 350 frame. [Stealthburner](https://github.com/VoronDesign/Voron-Stealthburner) and MiniStealthburner 
are an option but limited support. (Experimental version of the [Rapid Burner](https://github.com/chirpy2605/voron/tree/main/V0/Rapid_Burner) is in the works by @Marshalldog) (Experimental version for the [Xol-Toolhead](https://github.com/Armchair-Engineering/Xol-Toolhead) is in the works)
* Uses [OptoTap](https://www.google.com/search?q=optotap) probe sensor for nozzle Z probing.
* Same [rigidity](https://youtu.be/mGRXtK9F408) and probe accuracy as Tap.
* Same external printer dimensions, except for top hat.
* No servos, no wires on the shuttle, recommended to use with a Canbus toolhead board for less wires, but anything goes.

![Sovol Rebuild](/images/sovol-tapchanger/Dragon_Burner_Sovol-rebuild_fl.png)
![Voron Shuttle](/images/voron-tapchanger/shuttle-pomo.jpg)
![Voron Printer](/images/voron-tapchanger/printer.jpg) 

# Build guide

I would recommend to get a single hotend working first:

* Check the [BOM](/Tapchanger/BOM.md).
* [Print](./Print%20Guide.md) the parts.
* [Assemble](/Tapchanger/Assembly.md) it.

Multiple tools setup:
* Install [Umbilical](/Umbilical/Umbilical.md)

# Community



See Tapchanger from viesturz for the Voron 2.4[youtube channel](https://www.youtube.com/playlist?list=PLqU7kX5nUJDRDw5z0NLwJ22OkV6fbjnSW).

# Credits

- Dragon Burner from [chirpy2605](https://github.com/chirpy2605/voron/tree/main/V0/Dragon_Burner).
- Tapchanger from [viesturz](https://github.com/viesturz/tapchanger).


# Revision history:

## V0 - prototype
 
 - can't print at the time
