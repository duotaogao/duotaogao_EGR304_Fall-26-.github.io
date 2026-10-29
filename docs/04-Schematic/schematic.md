---
title: Schematic
---

## Overview

This schematic shows the user interface (UI) board for the GripRx project. A 9 V wall adapter enters through the barrel jack J3, passes the input protection (fuse F1 and diode D3), and feeds the L7805ABV-DG regulator U1, which creates the +5 V rail for the whole board. The PIC18F57Q43 Curiosity
Nano (U2) reads the START/STOP, UP and DOWN buttons, which use external 10 kΩ pull-up resistors with RC debouncing, drives the 16x2 character LCD in 4-bit mode (contrast set by RV1), and generates the feedback tones on its DAC output. Following the instructor's feedback, the audio path was simplified to one MCP6004 channel wired as an inverting amplifier with a gain of -2 (100 kΩ input resistor, 200 kΩ feedback resistor) and RV2 as the volume control; no separate buffer or low-pass filter stage is used. The board connects to the force sensing board through the 2x4 ribbon connector J1, which carries UART TX/RX, the UI_RUN signal and ground. A debug LED, a debug button, six test points, a spare GPIO header and the +5V-VTG and VOFF-GND jumpers support testing and troubleshooting.

**Note:** If the schematic image does not display, please download the schematic PDF using the link below. The schematic PDF is also submitted directly to Canvas.


![Schematic of the GripRx UI board](Screenshot.png)
**Figure 1:** Schematic of the GripRx UI board. [Open the full-resolution image](Screenshot.png).


## Resouces

The schematic as a PDF download is available [*here*](<Subsystem Schematic Design Duotao Gao.pdf>), and the Zip folder of the project [*here*](<Subsystem Schematic Design Duotao Gao.zip>).
