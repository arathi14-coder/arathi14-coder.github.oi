---
title: Individal Block Diagram
tags:
- tag1
- tag2
---

## Overview
The Spark Guard system operates at regulated 5 V DC level. Power from a 9 V 3 A source is stepped down using a Pololu 5 V 2.2 A Regulator. The Microchip PIC18F57Q43 Curiosity Nano acts as the main controller, processing digital inputs and driving both an LED indicator and a bidirectional solenoid through a H-Bridge. The circuit integrates all modules through a common 5 V supply for consistent operation.

***Power Source**
120 V AC mains converted to 9 V DC using an adapter

*Pololu 5 V Regulator supplies the entire circuit with a stable 5 V

**Inputs**
Digital Input 1: Armandoconnected to RB0 on the microcontroller.

Digital Input 2: Manny: connected to RB2 on the microcontroller.

**Actuator**
Red LED indicator for system status.

Bidirectional solenoid (SparkFun #11015) controlled through FAN8100N H-Bridge.


## Block Diagram 
The following image shows my individual block diagram created for the EGR 304 project, illustrating the current sensing and alert system using the PIC18F57Q43 Curiosity Nano microcontroller.
![Example of Indivial Block diagram ](Ayush_blockdiagram.drawio (4).png)

