# PCB Design
**Duotao Gao · EGR 304 · Team 103 GripRx · User Interface Board**
[Team website](https://egr304-2026-f-103.github.io/) | [Individual home](../index.md)
## Overview
Two-layer, through-hole PCB for the GripRx user interface subsystem, designed in KiCad 10. Gerber and drill files were checked using JLCDFM.

| Item | Value |
| --- | --- |
| Board size | 100 mm x 100 mm (limit 100 mm x 100 mm) |
| Layers | 2 copper (top and bottom), no solder mask, no silkscreen |
| Copper | 0.5 oz/ft² |
| Traces | 40 mil power and ground (+9V, +5V, GND, VTG), 20 mil signal, 15 mil minimum |
| Clearance | 10 mil minimum |
| Vias | 1.6 mm pad, 0.8 mm hole |
| Ground | GND pour on both layers, stitched with vias |
| Footprint library | DG_Footprints (custom footprints prefixed DG_) |
| DRC | 0 errors |

## PCB Layout
### Top
![Top copper layer](Duotao_PCB_Front.png)
### Bottom
![Bottom copper layer](Duotao_PCB_Back.png)
## Files
- [PCB layout, top and bottom (PDF)](Duotao_PCB_Layout.pdf)
- [KiCad project (ZIP)](Duotao_PCB_Project.zip)
- [Gerber and drill files (ZIP)](DuotaoGao103.zip)
## Layout Notes
The LCD circuitry has been removed. The Curiosity Nano connectors are positioned across the center of the board. The START/STOP, UP and DOWN buttons are along the bottom edge, with the debug button near the top-left corner. Connector J1 is below and to the left of the Nano connectors.
