---
title: Welcome
tags:
- tag1
- tag2
---
<center>
<font size= "8"> Ayush Rathi Datasheet</font><br>
as part of<br>
<font size= "6"> Spark Guard
<br>for
<font size= "5"> Team 203 </font><br>

**Submission: sept, 09, 2025**
</center>
<font size= "4">  
## Introduction

The Spark Guard is a smart extension cord designed to enhance electrical safety through automation and feedback. Using the PIC18F57Q43 Curiosity Nano as the main controller, Spark Guard detects unsafe conditions and automatically locks or unlocks the outlet cover using a bidirectional solenoid. An LED indicator provides a visual cue of current flow, ensuring users are aware when power is active.

### Project Summary

Spark Guard combines electrical safety and smart control in a compact design. The project team divided responsibilities into subsystems sensing, control, actuation and indication.

*The sensing module detects voltage, current, or voice commands.
*The control unit (PIC microcontroller) processes input data and sends signals to actuators.
*The actuation module operates a 5 V bidirectional solenoid through an H-Bridge driver to open or close the outlet lid.
*The indication system uses LEDs to show real-time status of current flow.

### My Contribution

* Connect and program the Microchip PIC18F57Q43 Curiosity Nano to control the H-Bridge.
* Configured the H-Bridge to drive a bidirectional solenoid that locks/unlocks the outlet lid.
* Integrated a status LED that turns ON when current is present and OFF when no current flows for user safety feedback.


To review the details listed of the material used to construct the subsection, you can review it in the ["BOM"](https://embedded-systems-design.github.io/EGR304DataSheetTemplate/03-BOM/BOM/) section of the datasheet.

For all the sections
 </font><br>
