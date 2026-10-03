# Custom PCB & Enclosure Design: 12V Linear Power Supply

This repository showcases an end-to-end electronic packaging project developed for the "Microelectronics and Packaging Techniques" course.
## Project Overview
The objective was to design, route, and package a custom 12V power supply utilizing an LM7805 linear voltage regulator. 

## Design Flow & Implementation

*   **Circuit Design & Schematic:** Designed a modified voltage regulator circuit, elevating the ground pin of the LM7805 via a resistor divider to achieve a 12V output from a 5V regulator.
*   **2D PCB Layout:** Performed component placement and automated routing, implementing a solid ground plane (Polygon pour) for shielding and proper return paths. 
*   **3D PCB Modeling:** Generated the 3D model of the assembled board, integrating custom `.step` files for external components like the DC-Jack connector.
*   **Mechanical Enclosure:** Designed a custom 3D-printable case featuring passive ventilation slots and precise cutouts for the power interface.
*   **Thermal Simulation:** Conducted heat transfer analysis using **SimScale** to evaluate the LM7805 TO-220 heatsink performance under free and forced convection scenarios for a 3W power dissipation

## Tools
*   **Software:** Autodesk Fusion 360 
*   **Thermal Analysis:** SimScale

