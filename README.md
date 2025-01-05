# ESP32-7in-EPaper-Weather-Station-Hardware

A weather station based on a Firebeetle ESP32 and a 7.5in Waveshare E-paper display. The data is fetched
from [Open-Meteo](https://open-meteo.com/).

## Build

### Hardware

#### Schematic

This repo is a KiCad project - open it to view the schematic. 

![Schematic preview](https://github.com/UnsignedArduino/ESP32-7in-EPaper-Weather-Station-Hardware/assets/38868705/f0b7ac98-3100-4367-87a3-94858c419a8a)

#### Case

This repo also contains the Fusion 360, 3MF, STEP, and STL file of the case I designed for this project. It uses some 3mm x 2mm neodymium magnets to hold the battery cover shut and a 4x D battery holder, with a metal bar replacing one of the D battery slots because the Firebeetle only accepts three 1.5v alkaline batteries connected to the regulator. 

### Software

You can find the code for it [here](https://github.com/UnsignedArduino/ESP32-7in-EPaper-Weather-Station).
