---
title: Welcome
---
<center>
<font size= "6">Duotao Gao Datasheet</font><br>
as part of<br>
<font size= "8"> GripRx</font><br>
for<br>
<font size= "5"> Team 103 </font><br>
</center>

## Introduction

This datasheet documents my individual contributions to the Team 103 design project for EGR 304, Fall 2026.

### Project Summary

Team 103 is designing **GripRx**, a prescription-based automatic-resistance grip trainer for hand rehabilitation. The device measures the force a patient applies through a load cell and automatically sets its own mechanical resistance to the level prescribed by a therapist. The system is split into three boards, each built around a PIC18F57Q43 Curiosity Nano: a user interface board, a force sensing board, and a motor board, connected in a daisy chain by 8-pin ribbon cables.

### My Contribution

I design the **user interface (UI) board**, one end of the daisy chain. It reads the START/STOP, UP and DOWN buttons, shows the session status on a 16×2 character LCD, plays feedback tones through a DAC, volume control, an MCP6004 inverting amplifier, and a speaker, and exchanges UART messages with the force sensing board.

## Datasheet Pages

- [Block Diagram](01-Block-Diagram/Block-Diagram.md): individual block diagram of the UI board
- [Component Selection](02-Component-Selection/Component-Selection.md): candidate parts, choices and rationale for each major component, and the microcontroller pin table
- [Power Budget](05-Power-Budget/Power-Budget.md): power budget for the UI board
- [Team Link](https://egr304-2026-f-103.github.io/): Team website link
- [Schematic](schematic.md): Schematic link
- [BOM](BOM.md):BOM link
