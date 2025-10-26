# OTA_IITB_esim_Marathon
Simulated 5 Transistor CMOS Operational Transconductance amplifier using esim - 2.5 for the IITB esim marathon.
# 5-Transistor CMOS OTA using eSim

### Project Overview
This project demonstrates the design and simulation of a **5-Transistor CMOS Operational Transconductance Amplifier (OTA)** using the open-source EDA tool **eSim** as part of the **IIT Bombay Open Source VLSI Design Marathon, FOSSEE**.


## Table of Contents
1. [Abstract](#abstract)  
2. [Reference Circuit Details](#reference-circuit-details)  
3. [Reference Circuit Diagram](#reference-circuit-diagram)
4. [Reference Circuit Waveform](#reference-circuit-waveform)
5. [Simulation in eSim](#simulation-in-esim)
   1. [DC Analysis](#dc-analysis)  
   2. [Circuit Schematic](#circuit-schematic)
   3. [Parameters for analysis](#parameters-for-analysis)
   4. [MOSFET Libraries](#mosfet-libraries)
   5. [Netlist](#netlist)
   6. [Output](#output)
   7. [Phase-2: AC Analysis](#phase-2:ac-analysis)
   8. [Circuit Schematic](#circuit-schematic)
   9. [Parameters for analysis](#parameters-for-analysis)
   10. [Netlist](#netlist)
   11. [Output](#output)
7. [Results](#results)  
8. [Conclusion](#conclusion)  
9. [Acknowledgement](#acknowledgement)  
10. [References](#references)


## Abstract
This project focuses on designing a 5-Transistor CMOS OTA using eSim to analyze its DC biasing and AC frequency response characteristics.  
The OTA is widely used in analog signal processing for its compact structure and differential input capability.


##  Reference Circuit Details
The OTA consists of a **differential input pair (M1, M2)**, an **active load (M3, M4)**, and a **current source transistor (M5)** that provides biasing.  
The simulation was carried out in **eSim - 2.5**.


## Reference Circuit Diagram
*<img width="785" height="751" alt="Screenshot 2025-10-26 175012" src="https://github.com/user-attachments/assets/d27f75e7-4c2a-42e5-98e3-7183a7f75b0b" />
*  


## Reference Circuit Waveform
<img width="780" height="650" alt="image" src="https://github.com/user-attachments/assets/6fb8cad5-64bc-4b24-9462-dedb90c44acc" />

## Simulation in eSim
This simulation was conducted in two phases.
Phase 1 (DC Analysis): The quiescent operating point (Q-point) was established to ensure all transistors operated in the saturation region. Temporary biasing was applied to the output transistor (M5), and final W/L ratios were optimized to meet the desired current levels.

Phase 2 (AC Analysis): The frequency response was evaluated to study the amplifier’s gain behavior. A cascode configuration using transistors M5 and M6 was introduced to enhance output resistance and voltage gain. Additionally, a load capacitor (CL) was added to form a dominant pole, ensuring stability and adequate phase margin for high-gain operation.


## DC Analysis

## Circuit Schematic
<img width="853" height="896" alt="image" src="https://github.com/user-attachments/assets/807cc09b-d3dd-4921-a751-727a8c12e2b9" />

## Parameters for analysis
<img width="1328" height="492" alt="image" src="https://github.com/user-attachments/assets/3f7ec522-ecdc-45a1-9eec-a9a5aaae68cf" />

<img width="1351" height="517" alt="image" src="https://github.com/user-attachments/assets/e4a9a5f4-830a-4975-b928-d404ba03d4ee" />

<img width="1287" height="313" alt="image" src="https://github.com/user-attachments/assets/adc477bb-f651-4705-8912-68c33c1984a9" />


<img width="1312" height="443" alt="image" src="https://github.com/user-attachments/assets/fd9293bf-a774-48c5-b059-f0f1cab23282" />

## MOSFET Libraries





