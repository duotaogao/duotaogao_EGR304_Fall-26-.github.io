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
### Style 2

> Also acceptable, more markdown friendly

**External Clock Module**

1. XC1259TR-ND surface mount crystal

    ![](image1.png)

    * $1/each
    * [link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Compatible with PSoC                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |

1. CTX936TR-ND surface mount oscillator

    ![](image3.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |

1. CTX936TR-ND surface mount oscillator

    ![](image3.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |
   
**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.

### Style 2

> Also acceptable, more markdown friendly

**External Clock Module**

1. XC1259TR-ND surface mount crystal

    ![](image1.png)

    * $1/each
    * [link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Compatible with PSoC                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |

1. CTX936TR-ND surface mount oscillator

    ![](image3.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |

1. CTX936TR-ND surface mount oscillator

    ![](image3.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |
   
**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.

### Style 2

> Also acceptable, more markdown friendly

**External Clock Module**

1. XC1259TR-ND surface mount crystal

    ![](image1.png)

    * $1/each
    * [link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Compatible with PSoC                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |

1. CTX936TR-ND surface mount oscillator

    ![](image3.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |

1. CTX936TR-ND surface mount oscillator

    ![](image3.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |
   
**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.

