---
title: Component Selection Example
---


1. Adafruit 412 (12 V Solenoid – 1528-1551-ND)

    ![](Screenshot%202025-10-27%20125659.png)

    * $7.50/each
    * [link to product](https://www.digikey.com/en/products/detail/adafruit-industries-llc/412/5819056)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Higher pulling force for heavier mechanical loads.                               | Needs separate 12 V supply |
    | Compatible with 12 V systems                      | Requires higher current, leading to more heat and power loss.                                        |
    |Compact and lightweight design |

2. Bidirectional Solenoid (SparkFun ROB-11015, 5 V DC)

    ![](Screenshot%202025-10-27%20100652.png)

    * $6.50/each
    * [Link to product](https://www.digikey.com/en/products/detail/sparkfun-electronics/11015/6163694)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Operates at 5 V DC, fully compatible with the voltage regulator                                            | could over heat when left energized for long    |
    | Compact open-frame design                                 | Short 4.5 mm stroke may limit motion range |
    | Low current draw allows safe operation via H bridge|

**Choice:** Option 2: Bidirectional Solenoid (SparkFun ROB-11015, 5 V DC)

**Rationale:*The SparkFun ROB-11015 5 V solenoid  provides the same push-pull capability at a lower voltage, making it completely compatible with the H-Bridge and 5 V power supply used in the Spark Guard project. As a result, there is no longer a requirement for an extra 12 V source, which lowers power losses and circuit complexity. 
