---
title: Schematic
---

## Overview

My final schematic represents the completed actuator subsystem for our Spark Guard project. The design integrates power regulation, microcontroller logic, manual debugging controls, team signal inputs, and a bidirectional solenoid driver. The board begins with a 9V DC input, which is then regulated to a stable 5V rail using an LM1085-5.0 voltage regulator. This provides sufficient current for both the PIC microcontroller and the H-Bridge responsible for solenoid actuation.

At the core of the design is the Microchip PIC18F57Q43 Curiosity Nano, which processes incoming digital signals and outputs control logic to drive the solenoid. Two input pins receive signals from my teammates’ PCB modules:

MIC_INT input – microphone subsystem output indicating activation.

CRT_INT input – current sensor subsystem signal used for system behavior/LED state.

The MCU then generates control outputs MIC_OUT1 and MIC_OUT2, which feed into the FAN8100N H-Bridge. Based on pin logic, the solenoid can be commanded to push or pull, enabling mechanical actuation in two directions. Local Open and Close push-buttons are included for standalone debugging and testing without teammate boards connected.


![schematic](Project 1 (1)-1.png){style width:"350" height:"300;"}
**Figure ##:** Showing a example schematic.


## Resouces

The schematic as a PDF download is available [*here*](Project 1 (1).pdf), and the Zip folder of the project [*here*](Project 1 ZIP.zip).
