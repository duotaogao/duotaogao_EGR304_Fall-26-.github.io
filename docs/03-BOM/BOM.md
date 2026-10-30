---
title: Bill of Materials
---
## Overview
This page lists every component on the GripRx user interface (UI) board, including the parts issued in class and the parts taken from the Peralta lab stock. The order quantity for each line is one per instance for the breadboard prototype, one per instance for the PCB, and one or two spares.
Debugging hardware (test points, jumpers, headers, the fuse holder and IC sockets) is included. Parts are grouped by vendor, and one purchase request was submitted for each vendor.

**Order total (my budget):** $__.__ · **Cost of one board (compare with MF-05, prototype BOM ≤ USD
150):** $__.__
Critical parts list a documented alternate, as required by MF-04.


## Bill of Materials
*Table 1: Bill of materials for the GripRx UI board, sorted by vendor.*

| **Part Name/Description** | **Qty/Board** | **Order Qty** | **Unit Cost** | **Total Cost** | **Manufacturer** | **Manufacturer #** | **Vendor Link** | **Datasheet** | **Ref Designators** |**Alternate** |
|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|
| 16x2 character LCD, 5 V, parallel, white LED backlight | 1 | 2 | $8.11 | $16.22 | Newhaven Display
| NHD-0216K1Z-FSW-FBW-L | [Digi-Key](https://www.digikey.com/en/products/detail/newhaven-displayintl/NHD-0216K1Z-FSW-FBW-L/1701185) | [PDF](datasheets/NHD-0216K1Z-FSW-FBW-L.pdf) | J4 | NHD-0216K1Z-FL-YBW |
| Speaker, 8 ohm, 36 mm, with leads | 1 | 3 | $2.17 | $6.51 | Same Sky | CMS-3652-28L200 | [DigiKey](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices/CMS-3652-28L200/29778294) | [PDF](datasheets/CMS-3652-28L200.pdf) | J5 (off-board) | CMS-4065-28L200 |
| ... continue with every Digi-Key line ... | | | | | | | | | | |
| 10 kΩ resistor, 1/4 W, axial THT | 6 | 14 | $0.00 | $0.00 | — | — | Peralta bin ___ | — | R7, R8,R9, R10, R14, R15 | — |
| ... continue with every Peralta line ... | | | | | | | | | | |
| PIC18F57Q43 Curiosity Nano | 1 | issued | — | — | Microchip | DM164150 | Issued in class | [PDF](datasheets/DM164150.pdf) | U2 | — |
| 5 V linear regulator, TO-220 | 1 | 3 | $1.04 | issued | STMicroelectronics | L7805ABV-DG | Issued in class | [PDF](datasheets/L7805ABV-DG.pdf) | U1 | LM2940CT-5.0 |
| Quad op amp, DIP-14 | 1 | 3 | $0.60 | issued | Microchip | MCP6004-I/P | Class kit | [PDF](datasheets/MCP6004.pdf) | U3 | MCP6024-I/P |
| 9 V 3 A AC/DC wall adapter | 0 (off-board) | issued | $4.52 | issued | BestCH | B09ZTKTLGW | Issued in class | — | — | GST18A09-P1J |

## Purchase Requests
- [Digi-Key purchase request (PDF)](Duotao_Gao_PR_DigiKey.pdf)
- [Peralta purchase request (PDF)](Duotao_Gao_PR_Peralta.pdf)
## Resources
The BOM spreadsheet is available [*here*](Duotao_Gao_BOM.xlsx).
