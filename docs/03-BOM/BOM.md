---
title: Bill of Materials
---

# Bill of Materials

**Duotao Gao · EGR 304 · Team 103 GripRx · User Interface Board**

**Email:** duotaoga@asu.edu  
**Date:** October 29, 2026

[Team website](https://egr304-2026-f-103.github.io/) | [Individual home](../index.md)

## Overview

This bill of materials covers the UI subsystem: PIC18F57Q43 Curiosity Nano, 5 V supply, LCD, user controls, MCP6004 audio circuit, speaker, connectors and debugging hardware. Provided materials remain listed. Purchases and Peralta stock requests are separated to avoid duplicate orders.

## Budget Summary

| Measure | Amount / treatment |
| --- | --- |
| Digi-Key order, including planned spares | $37.59 |
| Digi-Key parts for one UI subsystem, without spares | $14.81 |
| Peralta materials | Excluded from the course $60 per-member allowance |
| Development kits, free parts and out-of-pocket purchases | Excluded by course policy |
| Tax and shipping | Not quoted; budget treatment to be confirmed by instructor |

The $37.59 order is below the $60 per-member course allowance. It leaves $22.41 before any charges that the instructor determines should count. The $14.81 figure is the purchased-parts contribution for one UI subsystem, excluding Peralta and supplied inventory; it is not a valuation of every material. The team MF-05 target is $150 for the prototype and must be checked using the combined team BOM.

## Digi-Key Purchase Request

| Refs | Part / description | Manufacturer / MPN | Order qty | Unit USD | Total USD |
| --- | --- | --- | --- | --- | --- |
| J4 | 16 x 2 character LCD module | Newhaven Display / NHD-0216K1Z-FSW-FBW-L | 2 | $8.11 | $16.22 |
| C14 | Electrolytic capacitor, 220 uF 16 V | Rubycon / 16YXJ220MCR6.3X11 | 4 | $0.45 | $1.80 |
| C2 | Nonpolar ceramic capacitor, 0.33 uF 50 V | TDK / FA28X7R1H334KRU00 | 4 | $0.37 | $1.48 |
| C9 | Nonpolar ceramic capacitor, 1 uF 50 V (16 V minimum) | TDK / FG28X5R1H105KRT00 | 4 | $0.31 | $1.24 |
| R13 | Resistor, 200 kohm, 1/4 W | YAGEO / MFR-25FBF52-200K | 4 | $0.11 | $0.44 |
| D3 | Schottky diode, reverse-polarity protection | Taiwan Semiconductor / 1N5822 | 4 | $0.71 | $2.84 |
| J1 | Shrouded ribbon header, 2 x 4 | Wurth Elektronik / 61200821621 | 3 | $1.03 | $3.09 |
| J5 | Speaker screw terminal, 2 positions | On Shore Technology / OSTTE020161 | 3 | $0.67 | $2.01 |
| External speaker via J5 | Speaker, 8 ohm, 2 W | Same Sky / CMS-3652-28L200 | 3 | $2.17 | $6.51 |
| U1 heatsink | TO-220 heatsink | Advanced Thermal Solutions / ATS-PCBT1085 | 2 | $0.68 | $1.36 |
| JP1, JP2 shunts | Two-pin jumper shunt | Sullins / SPC02SYAN | 6 | $0.10 | $0.60 |

**Digi-Key materials subtotal: $37.59.**

## Peralta Stock Request

The remaining seven Peralta requests follow the [course-designated stock planning sheet](files/Peralta_Course_Order_Planning_Reference.xlsx). Quantities below are requests, not confirmation of receipt. The listed row numbers identify entries in the Fall 2022 worksheet; they are not physical shelf/bin numbers. Unit charges are not quoted, and no retail replacement price is assigned to unmarked stock.

| Refs | Required material | Requested qty | Source row |
| --- | --- | --- | --- |
| F1 | 1.5 A, 5 x 20 mm cartridge fuse | 4 | 87 |
| J3 | PJ-102AH through-hole DC barrel jack | 3 | 64 |
| RV1, RV2 | 10 kohm potentiometer, top-up after two owned units | 4 | 54 |
| U3 socket | 14-pin DIP socket, 7.62 mm row spacing | 3 | 78 |
| J4 PCB socket | 40-position 2.54 mm female header strip | 2 | 76 |
| F1 holder | 5 x 20 mm PCB fuse holder | 3 | 63 |
| Shared male header stock | 40-position 2.54 mm breakaway male header strip | 3 | 75 |

## Complete Component List

The list includes every schematic component and the required supplementary hardware. “Available” means reported available by the student; kit manufacturers and exact spare counts were not supplied. “Class-issued” follows the provided assignment planning reference.

| Refs | Part / description | Qty / system | Request qty | MPN / specification | Source / status |
| --- | --- | --- | --- | --- | --- |
| C3 | Nonpolar capacitor, 0.1 uF 50 V | 1 | 0 | — | Already available; no new order |
| C5, C8, C16, C17, C18, C19 | Nonpolar capacitor, 0.1 uF 16 V | 6 | 0 | — | Already available; no new order |
| C15 | Nonpolar capacitor, 0.1 uF 16 V, LCD VDD | 1 | 0 | — | Already available; no new order |
| D1 | Green LED, power indicator | 1 | 0 | — | Already available; no new order |
| D2 | Red LED, debug indicator | 1 | 0 | — | Already available; no new order |
| R1, R11 | Resistor, 1 kohm, 1/4 W | 2 | 0 | — | Already available; no new order |
| R5 | Resistor, 100 kohm, 1/4 W | 1 | 0 | — | Already available; no new order |
| R7, R8, R9, R10 | Resistor, 10 kohm, 1/4 W | 4 | 0 | — | Already available; no new order |
| R12 | Resistor, 330 ohm, 1/4 W | 1 | 0 | — | Already available; no new order |
| R14, R15 | Resistor, 10 kohm | 2 | 0 | — | Already available; no new order |
| R16 | Resistor, 330 ohm, 1/4 W | 1 | 0 | — | Already available; no new order |
| SW1 | Momentary pushbutton, START/STOP | 1 | 0 | — | Already available; no new order |
| SW2 | Momentary pushbutton, UP | 1 | 0 | — | Already available; no new order |
| SW3 | Momentary pushbutton, DOWN | 1 | 0 | — | Already available; no new order |
| SW4 | Momentary pushbutton, DEBUG | 1 | 0 | — | Already available; no new order |
| U1 | 5 V linear voltage regulator | 1 | 0 | L7805ABV-DG | Already available; no new order |
| U3 | Quad operational amplifier, PDIP-14 | 1 | 0 | MCP6004-I/P | Already available; no new order |
| U2 mating headers | Female headers for Curiosity Nano | 2 | 0 | — | Already available; no new order |
| External power adapter | External wall adapter, 9 V, 3 A | 1 | 0 | B09ZTKTLGW | Class-issued stock; confirm quantity |
| U2 | PIC18F57Q43 Curiosity Nano board | 1 | 0 | DM164150 | Class-issued stock; confirm receipt |
| C2 | Nonpolar ceramic capacitor, 0.33 uF 50 V | 1 | 4 | FA28X7R1H334KRU00 | Digi-Key |
| C9 | Nonpolar ceramic capacitor, 1 uF 50 V (16 V minimum) | 1 | 4 | FG28X5R1H105KRT00 | Digi-Key |
| C14 | Electrolytic capacitor, 220 uF 16 V | 1 | 4 | 16YXJ220MCR6.3X11 | Digi-Key |
| D3 | Schottky diode, reverse-polarity protection | 1 | 4 | 1N5822 | Digi-Key |
| J1 | Shrouded ribbon header, 2 x 4 | 1 | 3 | 61200821621 | Digi-Key |
| J4 | 16 x 2 character LCD module | 1 | 2 | NHD-0216K1Z-FSW-FBW-L | Digi-Key |
| J5 | Speaker screw terminal, 2 positions | 1 | 3 | OSTTE020161 | Digi-Key |
| R13 | Resistor, 200 kohm, 1/4 W | 1 | 4 | MFR-25FBF52-200K | Digi-Key |
| External speaker via J5 | Speaker, 8 ohm, 2 W | 1 | 3 | CMS-3652-28L200 | Digi-Key |
| U1 heatsink | TO-220 heatsink | 1 | 2 | ATS-PCBT1085 | Digi-Key |
| JP1, JP2 shunts | Two-pin jumper shunt | 2 | 6 | SPC02SYAN | Digi-Key |
| J6 | Spare GPIO header, 1 x 10, 2.54 mm | 1 | 0 | Cut from Peralta male strips | Included in shared strip allocation |
| JP1 | Two-pin jumper header, +5V-VTG | 1 | 0 | Cut from Peralta male strips | Included in shared strip allocation |
| JP2 | Two-pin jumper header, VOFF-GND | 1 | 0 | Cut from Peralta male strips | Included in shared strip allocation |
| TP1 | Test point | 1 | 0 | Cut from Peralta male strips | Included in shared strip allocation |
| TP2, TP3, TP4, TP5, TP6 | Test point | 5 | 0 | Cut from Peralta male strips | Included in shared strip allocation |
| J4 LCD male header | LCD male pin header, 1 x 16 | 1 | 0 | Cut from Peralta male strips | Included in shared strip allocation |
| F1 | 1.5 A, 5 x 20 mm cartridge fuse | 1 | 4 | Course-list specification | Peralta request |
| J3 | PJ-102AH through-hole DC barrel jack | 1 | 3 | Course-list specification | Peralta request |
| RV1, RV2 | 10 kohm potentiometer, top-up after two owned units | 2 | 4 | Course-list specification | Peralta request |
| U3 socket | 14-pin DIP socket, 7.62 mm row spacing | 1 | 3 | Course-list specification | Peralta request |
| J4 PCB socket | LCD 1 x 16 female socket, cut from 40-position stock | 1 | 2 x 40-position strips | Course-list specification | Peralta request |
| F1 holder | 5 x 20 mm PCB fuse holder | 1 | 3 | Course-list specification | Peralta request |
| Shared male header stock | 40-position 2.54 mm breakaway male header strip | Procurement stock | 3 | 2.54 mm breakaway male strips | Peralta request |
| J1 cable | Ribbon cable assembly, 8 conductors, 2 x 4 IDC ends | 1 | Team coordination | Team selection pending | Shared cable; purchaser/length not yet established |

## Quantity and Package Notes

- Quantities cover breadboard testing, PCB assembly and the planned spare allowance. Already-owned U1, U3, matching Nano headers and kit parts are not repurchased. Two 10 kohm pots are owned; four additional pots are requested to reach six.
- Two LCDs are requested: one can move from the breadboard to a socketed PCB, while the second provides a spare.
- Three 40-pin male strips provide 120 pins: LCD headers 48, J6 headers 30, jumper headers 12 and test points 14. Total allocated 104, leaving 16 spare. These pins are counted once.
- Two 40-position female strips provide three 16-position LCD sockets; allow sacrificial contacts when cutting.
- C14 is the selected Rubycon 220 uF 16 V part, D6.3 mm with 2.5 mm pitch; verify positive pad and 12.5 mm maximum seated-height clearance. C2 is the selected TDK 0.33 uF 50 V part, 5 mm pitch. Match the actual issued potentiometer and fuse-holder packages.
- Verify fuse response, DC plug dimensions/polarity, connector keying and all pin mappings. LCD module approval and the team cable are instructor/team review items.
- C9 remains a purchased nonpolar 1 uF ceramic. Polarized tantalum stock is not substituted. The specified 1N5822 and 200 kohm resistor remain on the purchase request.

## Manufacturer Documents and Purchasing Links

| Refs | MPN | Manufacturer document | Product / source |
| --- | --- | --- | --- |
| C2 | FA28X7R1H334KRU00 | [PDF](C2_TDK_FA.pdf) | [Product page](https://www.digikey.com/en/products/detail/tdk/FA28X7R1H334KRU00/7384656) |
| C9 | FG28X5R1H105KRT00 | [PDF](C9_TDK_FG.pdf) | [Product page](https://www.digikey.com/en/products/detail/tdk/FG28X5R1H105KRT00/7384818) |
| C14 | 16YXJ220MCR6.3X11 | [PDF](C14_Rubycon_YXJ.pdf) | [Product page](https://www.digikey.com/en/products/detail/rubycon/16YXJ220MCR6-3X11/5429971) |
| D3 | 1N5822 | [PDF](D3_1N5822.pdf) | [Product page](https://www.digikey.com/en/products/detail/taiwan-semiconductor-corporation/1N5822/7366597) |
| J1 | 61200821621 | [PDF](J1_61200821621.pdf) | [Product page](https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/61200821621/4846916) |
| J4 | NHD-0216K1Z-FSW-FBW-L | [PDF](J4_NHD-0216K1Z-FSW-FBW-L.pdf) | [Product page](https://www.digikey.com/en/products/detail/newhaven-display-intl/NHD-0216K1Z-FSW-FBW-L/1701185) |
| J5 | OSTTE020161 | [PDF](Terminal_OSTTE020161.pdf) | [Product page](https://www.digikey.com/en/products/detail/on-shore-technology-inc/OSTTE020161/614584) |
| R13 | MFR-25FBF52-200K | [PDF](R13_Yageo_MFR.pdf) | [Product page](https://www.digikey.com/en/products/detail/yageo/MFR-25FBF52-200K/13547) |
| U1 | L7805ABV-DG | [PDF](U1_ST_L78.pdf) | [Product page](https://www.digikey.com/en/products/detail/stmicroelectronics/L7805ABV-DG/497-15681-5-ND/3945936) |
| U2 | DM164150 | [PDF](U2_DM164150_UserGuide.pdf) | [Product page](https://www.digikey.com/en/products/detail/microchip-technology/DM164150/11586705) |
| U3 | MCP6004-I/P | [PDF](U3_MCP6004.pdf) | [Product page](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060) |
| External speaker via J5 | CMS-3652-28L200 | [PDF](Speaker_CMS-3652-28L200.pdf) | [Product page](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices/CMS-3652-28L200/29778294) |
| U1 heatsink | ATS-PCBT1085 | [PDF](U1_Heatsink_ATS_Catalog.pdf) | [Product page](https://www.digikey.com/en/products/detail/advanced-thermal-solutions-inc/ATS-PCBT1085/5030505) |
| JP1, JP2 shunts | SPC02SYAN | [PDF](JP_Shunt_SPC02SYAN.pdf) | [Product page](https://www.digikey.com/en/products/detail/sullins-connector-solutions/SPC02SYAN/76375) |

Provided generic parts use the specifications in the course stock list. Manufacturer family documents are references; select PCB footprints from the actual issued part. Archived alternative documents do not establish the identity of unmarked stock.

## Alternate Candidates

| Use | Candidate | Review needed |
| --- | --- | --- |
| LCD | NHD-0216K1Z-FLYBW | Voltage, pinout, dimensions and course approval |
| U1 | LM2940CT-5.0 | Different capacitor/stability requirements |
| U3 | MCP6024-I/P | Operating range, output performance and pinout |
| Speaker | CMS-4065-28L200 | Dimensions, impedance and sound output |
| External adapter | GST18A09-P1J | Plug dimensions, polarity and course approval |

These are candidates for review, not pre-approved interchangeable parts.

## Files

- [Full BOM spreadsheet](Duotao_Gao_BOM_Updated.xlsx)
- [BOM page PDF](Duotao_Gao_BOM_Page.pdf)
- [Digi-Key request XLSX](Duotao_Gao_DigiKey_Purchase_Request.xlsx) · [PDF](Duotao_Gao_DigiKey_Purchase_Request.pdf)
- [Peralta request XLSX](Duotao_Gao_Peralta_Purchase_Request.xlsx) · [PDF](Duotao_Gao_Peralta_Purchase_Request.pdf)
- [Digi-Key bulk-upload CSV](DigiKey_Bulk_Upload.csv)

## AI Assistance

ChatGPT assisted with transcription of supplied schematic/BOM information, price lookup, quantities, source classification, calculations and document formatting. The student supplied inventory information and the email address. Actual part receipt, physical compatibility and instructor approval are not claimed. [Prompts and disclosure](AI_Disclosure.md).

## Resources

