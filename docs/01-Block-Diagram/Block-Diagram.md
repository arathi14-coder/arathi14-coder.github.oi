---
title: Individal Block Diagram
tags:
- tag1
- tag2
---

## Overview
The Spark Guard actuator subsystem is designed to physically lock and unlock the system using a bidirectional solenoid. I am responsible for the solenoid actuation board which receives signals from two of my teammates and performs the mechanical movement using an H-Bridge. Power for the entire system originates from a 9V 3A, DC supply, which is stepped down to 5V using a Texas Instruments 5V 2.2A voltage regulator. The central controller for this subsystem is the PIC18F57Q43 Curiosity Nano, which interprets incoming digital signals and drives the solenoid accordingly.

Two push buttons are included for manual debugging, allowing local control of PUSH (extend) and PULL (retract) movement without needing external input.

***Power Source**
120 V AC mains converted to 9 V DC using an adapter

*Texas Instruments 5V 2.2A voltage regulator supplies the entire circuit with a stable 5 V

**Inputs**
Digital Input 1: Armandoconnected to connector 1 on the microcontroller, indicating when to turn ON the LED.

Digital Input 2: Manny: connected to connector 2 on the microcontroller, indicating when to actuate the solenoid (open/close event request).

**Actuator**
Red LED indicator for system status.

Bidirectional solenoid (SparkFun #11015) controlled through FAN8100N H-Bridge.


## Block Diagram 
The following image shows my individual block diagram created for the EGR 304 project, illustrating the current sensing and alert system using the PIC18F57Q43 Curiosity Nano microcontroller.
![Example of Indivial Block diagram ](Ayush_blockdiagram.drawio (4).png)

