# Tapchanger for Sovol SV08

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


# Build guide

Dont't have a BOM at the time.

see [CAD](\Sovol-Tapchanger\CAD\Dragon_Burner_Sovol-rebuild.step) file and print with FDM Printer:
* black extruder part (Nylon 12 CF, ABS, ...)
* green part (PLA, PETG, ...)
* orange part (Nylon 12 CF, ABS, ...)
* red and blue part (Nylon 12 CF, ABS, ...)

to print with SLA or you can test with FDM:
* Gearhousing at the extruder black part

# Community

See Tapchanger from viesturz for the Voron 2.4 [youtube channel](https://www.youtube.com/playlist?list=PLqU7kX5nUJDRDw5z0NLwJ22OkV6fbjnSW).

# Credits

- Dragon Burner from [chirpy2605](https://github.com/chirpy2605/voron/tree/main/V0/Dragon_Burner).
- Tapchanger from [viesturz](https://github.com/viesturz/tapchanger).


# Revision history:

## V0 - prototype
 
 - is not tested at the time
 - need help with CAN-BUS and the Sovol Extruder bord
