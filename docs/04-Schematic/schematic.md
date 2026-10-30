---
title: Schematic
---

## Overview

This schematic shows the user interface (UI) board for the GripRx project. A 9 V wall adapter enters through the barrel jack J3, passes the input protection (fuse F1 and diode D3), and feeds the L7805ABV-DG regulator U1, which creates the +5 V rail for the whole board. The PIC18F57Q43 Curiosity
Nano (U2) reads the START/STOP, UP and DOWN buttons, which use external 10 kΩ pull-up resistors with RC debouncing, drives the 16x2 character LCD in 4-bit mode (contrast set by RV1), and generates the feedback tones on its DAC output. Following the instructor's feedback, the audio path was simplified to one MCP6004 channel wired as an inverting amplifier with a gain of -2 (100 kΩ input resistor, 200 kΩ feedback resistor) and RV2 as the volume control; no separate buffer or low-pass filter stage is used. The board connects to the force sensing board through the 2x4 ribbon connector J1, which carries UART TX/RX, the UI_RUN signal and ground. A debug LED, a debug button, six test points, a spare GPIO header and the +5V-VTG and VOFF-GND jumpers support testing and troubleshooting.

**Note:** If the schematic image does not display, please download the schematic PDF using the link below. The schematic PDF is also submitted directly to Canvas.


![Schematic of the GripRx UI board](Screenshot.png)
**Figure 1:** Schematic of the GripRx UI board. [Open the full-resolution image](Screenshot.png).

## Relationship to User Needs and Product Requirements

The UI board provides controls and feedback for patients using the GripRx rehabilitation device. The START/STOP, UP and DOWN buttons allow the user to control a session and adjust settings. External pull-up resistors establish defined input levels, while RC networks help reduce switch bounce. Software debouncing will also be evaluated during testing.

The 16x2 LCD is intended to display grip force, resistance level and repetition information. This supports UX-02 and UX-03 by presenting exercise progress to the user. The display layout, force resolution and refresh rate will be verified during software integration.

The audio circuit provides feedback without requiring the user to continuously watch the display. The DAC signal passes through the RV2 volume control and an MCP6004 inverting amplifier with a nominal AC gain of -2. C14 blocks DC from the speaker, and R16 limits output current. This circuit is intended to support the audible notification requirement in UX-05. Compliance with the 65 dBA target at 0.5 m has not yet been demonstrated and requires prototype testing.

Connector J1 carries UART signals, UI_RUN and a common ground between the UI board and the force sensing board. The boards use separate local power supplies; the ribbon cable does not distribute power. The input fuse and reverse-polarity diode provide electrical protection, while the 5 V regulator supplies the UI circuitry.

Six test points, power-isolation jumpers, an IC socket and debugging connections support assembly and troubleshooting. Reusing class-provided components also helps control prototype cost. Final compliance with the team requirements will be evaluated through subsystem testing and team integration.

## Use of Generative AI

I used ChatGPT (OpenAI) for this assignment. ChatGPT helped explain the schematic requirements, review component connections and labels, and draft and revise the webpage overview and discussion of product requirements. I provided schematic screenshots, course materials and instructor feedback, and made the changes in KiCad and on the webpage. Hardware operation remains to be tested.

My requests included:

1. Reviewing the schematic for missing components and connections.
2. Explaining component functions and reference designators.
3. Checking consistency between the schematic and webpage descriptions.
4. Helping describe how the UI board addresses user needs and product requirements.
5. Improving the wording and formatting of the schematic webpage.


## Resouces

The schematic as a PDF download is available [*here*](<Subsystem Schematic Design Duotao Gao.pdf>), and the Zip folder of the project [*here*](<Subsystem Schematic Design Duotao Gao.zip>).
