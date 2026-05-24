# CE-ESY-assignments2
# Lab Assignment 2: STM32F103C8T6 (Blue Pill) Schematic

## Project Description
This repository contains the completed Schematic Diagram for the **STM32F103C8T6 (Blue Pill)** microcontroller board, designed using **KiCad v9**. The schematic has been modified and optimized according to the lab instructions and component datasheets.

## Key Modifications & Features
* **Voltage Regulator:** Updated to **LM1117-3.3** with proper input/output decoupling capacitors ($10\mu\text{F}$) for optimal power stability.
* **Decoupling Capacitors:** Standardized decoupling capacitor values around the MCU using the 104 reference.
* **Component Optimization:** Removed unused components ($C_9$, $C_{12}$, and $Y_3$) as specified in the lab notes.
* **ERC Clean:** Cleared all Electrical Rules Check (ERC) errors, verified all pin connections, and properly flagged unused pins with No-Connect markers.

## Repository Structure
* `CE-ESY-assignments/`
    * `Lab/`
        * `Assignment1/`
            * `STM32F103C8T6 - Blue Pill.kicad_sch` (Main Schematic File)
            *  `STM32F103C8T6 - Blue Pill.pdf`
            * `README.md` (This documentation file)

---
**Designed By:** Aryam Almural  
**Date:** 24 May 2026
