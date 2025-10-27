---
title: Component Selection Example
---

## Examples

**External Clock Module**

1. XC1259TR-ND surface mount crystal

    ![](Screenshot%202025-10-27%20100652.png)

    * $1/each
    * [link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Compatible with PSoC                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |

1. Bidirectional Solenoid

    ![](image3.png)

    * $6.50/each
    * [Link to product](https://www.digikey.com/en/products/detail/sparkfun-electronics/11015/6163694)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Operates at 5 V DC, fully compatible with the voltage regulator                                            | could over heat when left energized for long    |
    | Compact open-frame design                                 | Short 4.5 mm stroke may limit motion range |
    | Low current draw allows safe operation via H bridge|

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.
