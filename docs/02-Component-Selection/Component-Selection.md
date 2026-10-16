---
title: Component Selection Example
---

**External Clock Module**

1. CMS-4065-28L200 speaker

    ![](image1.png)

    * $4.68/each
    * [link to product](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices/CMS-4065-28L200/29566827?s=N4IgTCBcDaIMoAcCmBDA1kgTgZwAQGEBZOAWgBYAGANgFYSwAOAGTAopAF0BfIA)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | It comes with a lead wire for easy connection. | A diameter of 40mm is relatively large |
    | Impedance 8Ω, rated input power 2W. |  The unit price of $4.68 is relatively high.               |
    |  |

2. CMS-3652-28L200 speaker

    ![](image2.png)

    * $2.17 /each
    * [Link to product](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices/CMS-3652-28L200/29778294?s=N4IgTCBcDaIMoAcCmBDA1kgTgZwAQGEBZOAWgGYA2AVjBLAA4AZMABhZAF0BfIA)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Both are 8Ω                                             | The nominal diameter is 36mm, and sufficient installation space needs to be reserved inside the casing.      |
    | Rated at 2W                                | The manufacturer suggests using it in conjunction with the casing, but additional considerations need to be given to the fixed structure and acoustic design. |
    |  Nominal 36mm, with the lowest price at $2.17. |

3. CMS-36205-28L200 speaker

    ![](image3.png)

    * $4.73/each
    * [Link to product](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices/CMS-36205-28L200/28173784?s=N4IgTCBcDaIMIFkDKBaAzANjABgKwrAA4AZHbEAXQF8g)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | 36.2×20.5mm oval                                             | The maximum unit price is $4.73     |
    | Suitable for narrower Spaces                                 | Different installation shapes|
    |  |
   
**Choice:** Option 2: CMS-3652-28L200 speaker

**Rationale:** I chose the CMS-3652-28L200 because it is low in price, compact in size and comes with leads, making it a suitable candidate as a speaker for the UI board. Its 8Ω impedance and 2W rated input power comply with the planned specifications to be adopted. Subsequently, we will verify whether the prompt sound is clear and audible in conjunction with the actual power amplifier and the casing.



**LED panel**

1. NHD-0216K1Z-FL-YBW LED panel 

    ![](image4.png)

    * $7.83/each
    * [link to product](https://www.digikey.com/en/products/detail/newhaven-display-intl/NHD-0216K1Z-FL-YBW/1701171?s=N4IgTCBcDaIHIAkAiBaADGAjANgNKYC0UAxAGRQE0AhAdRAF0BfIA)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | The 5V power supply complies with the power rail planned to be adopted by the UI board.    | The typical current of the backlight at 5V is 130mA, which needs to be included in the power supply budget. |
    | Semi-transparent reflective screens can display by using ambient light.   | When using a 4-bit write-only connection method, six GPIO signal lines are required.                                       |
    |  |

2. NHD-0216K1Z-FSW-FBW-L LED panel

    ![](image5.png)

    * $8.11/each
    * [Link to product](https://www.digikey.com/en/products/detail/newhaven-display-intl/NHD-0216K1Z-FSW-FBW-L/1701185?s=N4IgTCBcDaIHIAkAiBaADGAjANgNKYC0UAxAZQHUSAhSgGRAF0BfIA)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | The typical current of the backlight at 5V is only 15mA, which helps to control the power supply burden.      | The 16×2 character format limits the amount of information that can be displayed at one time.      |
    | The FSTN positive display screen features a light background with dark text, making it suitable for showing text readings.      | The V0 pin requires an external contrast voltage setting to add a regulating connection. |
    | |

3. NHD-0216K1Z-NSW-BBW-L LED panel

    ![](image6.png)

    * $7.44/each
    * [Link to product](https://www.digikey.com/en/products/detail/newhaven-display-intl/NHD-0216K1Z-NSW-BBW-L/1701179?s=N4IgTCBcDaIHIAkAiBaADGAjANgNKYC0U4BlAdRQCFKKAZEAXQF8g)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Supports 5V power supply and parallel interface.                                           | Transmissive screens rely on backlighting to obtain readable displays.    |
    | The white backlight makes it convenient to view the content in a darker environment.                                 | The character layout cannot present a complete graphical user interface.|
    |  |
   
**Choice:** Option 2: NHD-0216K1Z-FSW-FBW-L LED panel

**Rationale:** I choose Option 2 because it conforms to the planned 5V power supply, parallel interface and 16×2 character format, with a typical backlight current of 15mA. Although the base price has increased by $0.82, the typical backlight current has been reduced from 130mA to 15mA, which helps to alleviate the power supply burden on the UI board.


**low pass filter**

1. MCP6004-I/P low pass filter

    ![](image7.png)

    * $0.6/each
    * [link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060?s=N4IgTCBcDaILIGEAKA2ADGgLAWgJIHokQBdAXyA)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Supports 5V power supply                             | The MHz gain bandwidth is limited for high-frequency and high-gain design |
    | DIP package simplifies breadboard prototyping                      | In the four-way operational amplifier structure, the unused channels need to be connected correctly.                                       |
    |  |

2. MCP6024-I/P low pass filter

    ![](image8.png)

    * $2.73/each
    * [Link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6024-I-P/417834?s=N4IgTCBcDaILIGEAKA2ADGALAWgJIHokQBdAXyA)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | A 10 MHz gain-bandwidth product provides design margin.                                            | Typical quiescent current is approximately 1 mA per channel.      |
    | DIP package allows easy assembly and replacement.                                | Unused channels occupy space and require proper termination.|
    | |

3. TLV9004IPWR low pass filter

    ![](image9.png)

    * $0.91/each
    * [Link to product](https://www.digikey.com/en/products/detail/texas-instruments/TLV9004IPWR/9674912?s=N4IgTCBcDaICoBkBqBOADGgLASQAoHUAlEAXQF8g)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    |  Supports 5V power supply.                                            | When TSSOP packaging is used for breadboards, an adapter board is required.     |
    |  The typical quiescent current per channel is approximately 60µA.                               | The maximum working power supply is 5.5V and it cannot be directly connected to a 9V power source. |
    | |
   
**Choice:** Option 1: MCP6004-I/P

**Rationale:** I choose MCP6004-I/P as the operational amplifier for the active low-pass filter. It supports 5V power supply for the system. The DIP packaging makes it convenient to build and debug on the breadboard, while remaining consistent with the existing block diagram.


**audio power amplifier**

1. LM386N-1/NOPB audio power amplifier

    ![](image10.png)

    * $1.18/each
    * [link to product](https://www.digikey.com/en/products/detail/texas-instruments/LM386N-1-NOPB/6284?s=N4IgTCBcDaIDIFkDMAOAbAOQLQEYD0GA8gAoBCIAugL5A)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Supports 5V power supply                               | The output power is limited under low-voltage power supply, and the volume of the prompt tone needs to be verified. |
    | DIP packaging facilitates the construction of breadboards.      |  Conventional single-ended circuits require output coupling capacitors, which occupy additional space.                              |
    | |

2. LM4861M/NOPB audio power amplifier

    ![](image11.png)

    * $1.81/each
    * [Link to product](https://www.digikey.com/en/products/detail/texas-instruments/LM4861M-NOPB/334832?s=N4IgTCBcDaIDIFkAsAOAbARgQegHIHkAFAIRAF0BfIA)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    |  Under the conditions of 5V, 8Ω and 1% THD+N, the typical output power is 1.1W.          | When SOIC packaging is used for breadboards, an adapter board is required.     |
    | Bridging output does not require an output coupling capacitor.                          | In bridge mode, both ends of the speaker must be connected to the amplifier output and cannot be grounded. |
    | |

3. LM4871M/NOPB audio power amplifier


    ![](image12.png)

    * $1.92/each
    * [Link to product](https://www.digikey.com/en/products/detail/texas-instruments/LM4871M-NOPB/364185?s=N4IgTCBcDaIDIFkAsAOA7ARgQegHIHkAFAIRAF0BfIA)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    |  Supports 5V power supply and 8Ω speakers.          |  SOIC packaging requires an adapter board to be inserted into the breadboard.   |
    |  It provides an off mode to reduce power consumption when no sound is being played.                             | When the output power is high, it is necessary to check the heat dissipation of the chip and the power supply capacity of the power supply. |
    |  |
   
**Choice:** Option 1: LM386N-1/NOPB audio power amplifier

**Rationale:** I chose the LM386N-1/NOPB as the power amplifier for the prompt sound circuit because it supports 5V power supply for the system and its DIP package makes it convenient for breadboard assembly and debugging. Its built-in voltage gain reduces the external gain setting components, making it suitable for the simple mono prompt sound function of this project.

**5V Voltage Regulator**

1. L7805CV 5V Voltage Regulator

    ![](image13.png)

    * $1.08/each
    * [link to product](https://www.digikey.com/en/products/detail/stmicroelectronics/L7805CV/585964)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | A fixed 5V output is required, and there is no need to set the resistor for the output voltage.          | The input and output voltage differences are converted into heat, and heat dissipation is required when there is a large current. |
    |  The TO-220 in-line package is easy TO assemble and comes with overheat and short-circuit protection.  | The input voltage must be higher than 5V and a voltage stabilization margin should be left.                                        |
    |  |

2. LM2940CT-5.0/NOPB 5V Voltage Regulator

    ![](image14.png)

    * $2/each
    * [Link to product](https://www.digikey.com/en/products/detail/texas-instruments/LM2940CT-5-0-NOPB/32575?s=N4IgTCBcDaIDIFkwE4AsAGAwgFQLQFYA6dAegDkB5ABQCEQBdAXyA)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Fixed 5V output, supporting 1A output current, and heat dissipation conditions must be met.    | The output capacitance must be at least 22µF and must meet the ESR requirements.     |
    | At 1A, the typical pressure difference is approximately 0.5V.   | Even when the temperature drops from 9V to 5V, significant heat is still generated. |
    |  |

3. R-78B5.0-1.0 5V Voltage Regulator

    ![](image15.png)

    * $12.17/each
    * [Link to product](https://www.digikey.com/en/products/detail/recom-power/R-78B5-0-1-0/2256232)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Supports 6.5-32V input and provides 5V, 1A output.              |  There are switching ripples and noise. Audio circuits need to pay attention to filtering and layout.   |
    | The switch has a high conversion efficiency and can reduce heat loss during the voltage reduction process.                 | The module has a minimum load recommendation. When the load is light, the output performance needs to be checked. |
    |  |
   
**Choice:** Option 1: L7805CV 5V Voltage Regulator

**Rationale:** I chose the L7805CV to convert the 9V input to the 5V required by the system. It provides a fixed output voltage without the need for additional voltage setting resistors. The TO-220 through-hole package facilitates breadboard assembly and debugging. The built-in overheat and short-circuit protection is also suitable for the power circuit of this project.

**External Clock Module**

1. XC1259TR-ND surface mount crystal

    ![](image13.png)

    * $1/each
    * [link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Compatible with PSoC                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |

1. CTX936TR-ND surface mount oscillator

    ![](image14.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |

1. CTX936TR-ND surface mount oscillator

    ![](image15.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |
   
**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.

