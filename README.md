# Rectangular Waveguide Field Analysis

## Overview
This project explores the behavior of electromagnetic fields in rectangular waveguides, which are essential components in microwave and RF engineering. Using ANSYS HFSS, the study visualizes transverse electric (TE) and transverse magnetic (TM) modes, analyzing how electric and magnetic fields distribute across XY, XZ, and YZ planes. Surface current density along the waveguide walls is also examined to understand wave-structure interactions. These insights enable optimized waveguide design, efficient energy transmission, and high-performance signal propagation in applications such as satellite communications, radar systems, and advanced sensing technologies.

## Objective
- Analyze TEmn and TMmn modes in rectangular waveguides.
- Visualize field patterns across multiple planes and frequency bands.
- Examine surface current density to assess energy propagation and waveguide performance.

## Simulation Procedure
1. **Define Simulation Frequency Band:** Set up a frequency sweep (e.g., 8–12 GHz) during the analysis setup in ANSYS HFSS.
2. **Set Excitation and Modes:** Define the input port excitation; the dominant TE10 mode is typically excited by default. Adjust port setup for advanced mode control if required.
3. **Select Field Type:** Post-simulation, choose the field to visualize:
   - Electric Field  
   - Magnetic Field  
   - Surface Current Density
4. **Mode Indices (m, n):** Ensure proper mode excitation by setting waveguide dimensions and operating frequencies above the cutoff frequency.
5. **Visualize Field Patterns:** Use ANSYS HFSS post-processing tools to display field distributions across XY, XZ, and YZ planes.

## Tools & Technologies
- **Simulation Software:** ANSYS HFSS  
- **Domain:** Microwave and RF Engineering  
- **Key Concepts:** TE/TM Modes, Surface Current Density, Waveguide Design Optimization

## Applications
- Satellite communications  
- Radar and sensing systems  
- Medical imaging and high-frequency signal transmission
- 
## Author
**[Semalign Markos]** – Aspiring Electronic Communication Engineer  
GitHub: [your-github-link]  

## License
This project is licensed under the MIT License.
