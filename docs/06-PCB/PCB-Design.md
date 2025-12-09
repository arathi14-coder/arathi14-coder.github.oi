---
title: PCB Design
---

## 3D Renders from KiCad

**Description**  
These 3D renders show the current PCB layout from KiCad. The board includes:
- PIC18F57Q43 microcontroller footprint
- MSR5-0R005F1 5V, 2.2 A regulator 
- FAN8100N H-bridge driver
- Red LED indicator
- Solenoid connection terminals and I/O headers

![Front view ](Screenshot 2025-12-09 075928.png){style="width:350px; height:300px;"}

![back view](Screenshot 2025-12-09 075928.png){style="width:350px; height:300px;"}


The PCB file download is available [*here*](Project 1 (1).kicad_pcb)

## ECAD Layout

**[Open PCB PDF](06-PCB/Geber Project 1.pdf)**
<embed src="gerbers/pcb_gerber.pdf" type="application/pdf" width="100%" height="600px" />


**Layout Notes**
- High-current traces for the solenoid are widened on the 5 V path.
- Decoupling capacitors are placed close to the regulator and IC power pins.
- A ground plane on the back layer helps with signal integrity and heat spreading.
- Component placement is optimized for debugging and measurement access.


The Geber file as a PDF download is available [*here*](Geber Project 1.pdf), and a ZiP file of it aswell [*here*](Project 1 (1)-F_Mask.zip).
