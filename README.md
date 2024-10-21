# 1bitFullAdder_RTL2GDSFlow
RTL to GDSII Flow for 1-Bit Full Adder
Project Overview
This project demonstrates the complete RTL to GDSII design flow using a 1-bit Full Adder as the core example. The flow involves various stages such as RTL design, logic synthesis, physical design, and design validation. The primary goal is to transform high-level RTL code into a manufacturable GDSII layout, suitable for chip fabrication.

Project Details
Title: RTL to GDSII Flow for 1-bit Full Adder
Submitted By:
Akash Pandey (2302102035)
Shivam Vaish (2302102034)
Institution: Indian Institute of Technology, Indore
Supervisor: Dr. Santosh Kumar Vishwakarma
Date: November 15, 2023
Course: M.Tech (VDN) - Practical Coursework
Tools Used
The project utilized several industry-standard tools for different stages of the design flow:

Incisive (SimVision): For RTL simulation and functional verification.
Genus: For logic synthesis and conversion of RTL to gate-level logic.
Modus: For static timing analysis to ensure the design meets timing requirements.
Conformal: For logic equivalence checking (LEC) between RTL and gate-level netlists.
Innovus: For physical design, including placement, routing, and GDSII generation.
Key Steps in the Design Flow
RTL Design:

The RTL code for a 1-bit Full Adder was written using Verilog/VHDL.
Functional verification was performed to ensure correct design operation.
Synthesis:

The RTL code was synthesized into a gate-level netlist using Cadence Genus.
Timing, power, and area optimizations were conducted.
Physical Design:

Floorplanning, placement, clock tree synthesis (CTS), and routing were completed using Innovus.
Detailed routing and Design Rule Check (DRC) were performed to ensure manufacturability.
Verification:

Logic equivalence checks (LEC) were performed using Conformal to ensure that the gate-level netlist matched the RTL description.
Static timing analysis ensured that the design met performance goals.
Tapeout:

The final GDSII file was generated, marking the end of the back-end design process. This file is ready for chip fabrication.
Project Structure
/src: Contains the RTL code for the Full Adder.
/simulation: Includes the testbenches and simulation results.
/synthesis: Synthesis scripts and output files.
/physical_design: Floorplanning, placement, routing, and timing reports.
/docs: Project documentation, reports, and final GDSII layout.
Acknowledgments
We would like to express our gratitude to Dr. Santosh Kumar Vishwakarma for his continuous guidance and support throughout this project. Special thanks to NSDCS Ph.D. scholars, Mr. Mukul and Ms. Vasundhara, for their assistance and to our fellow M.Tech students for their motivation.
