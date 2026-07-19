# FPGA_Fabric_Design_Architecture


> Comprehensive documentation of the complete FPGA implementation
> flow---from RTL design to FPGA fabric generation---using
> industry-standard and open-source FPGA CAD tools.

------------------------------------------------------------------------

## Overview

This repository documents the hands-on work carried out during the
**FPGA Fabric Design and Architecture Workshop**. It covers the complete
FPGA design flow, including RTL development, simulation, synthesis,
placement, routing, timing analysis, power estimation, FPGA architecture
exploration, and post-implementation verification.

The workshop emphasizes understanding how a Verilog RTL design is
transformed into a hardware implementation on an FPGA using modern FPGA
CAD frameworks.

The implementation flow includes:

-   RTL Design
-   Functional Simulation
-   Logic Synthesis
-   Technology Mapping
-   Placement
-   Routing
-   Static Timing Analysis (STA)
-   Resource Utilization Analysis
-   Power Analysis
-   FPGA Fabric Generation
-   Post-Implementation Simulation

------------------------------------------------------------------------

## Tools & Frameworks

  -----------------------------------------------------------------------
  Tool                         Purpose
  ---------------------------- ------------------------------------------
  **Vivado**                   RTL simulation, synthesis, implementation,
                               and analysis

  **VTR (Verilog-to-Routing)** Open-source FPGA CAD flow

  **VPR (Versatile Place and   Placement, routing, and timing analysis
  Route)**                     

  **OpenFPGA**                 FPGA fabric generation and architecture
                               exploration

  **SOFA FPGA**                Custom FPGA architecture framework

  **Verilog HDL**              RTL design

  **SDC**                      Timing constraints
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## Repository Structure

  -----------------------------------------------------------------------
  Day              Topics Covered
  ---------------- ------------------------------------------------------
  **Day 1**        FPGA fundamentals, Vivado simulation, Verilog basics,
                   4-bit counter design

  **Day 2**        VTR flow, EArch FPGA architecture, SDC constraints,
                   placement, routing, timing and utilization reports

  **Day 3**        RVMYTH RISC-V processor implementation, FPGA analysis,
                   ILA debugging

  **Day 4**        Post-synthesis simulation, primitive models, timing
                   verification

  **Day 5**        RISC-V implementation on SOFA FPGA using OpenFPGA
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# Design Flow

``` text
RTL Design
     │
     ▼
Functional Simulation
     │
     ▼
Logic Synthesis
     │
     ▼
Technology Mapping
     │
     ▼
Placement
     │
     ▼
Routing
     │
     ▼
Timing & Power Analysis
     │
     ▼
FPGA Fabric Generation
     │
     ▼
Post-Implementation Verification
```

------------------------------------------------------------------------

# Topics Covered

## FPGA Fundamentals

-   FPGA Architecture
-   Configurable Logic Blocks (CLBs)
-   Look-Up Tables (LUTs)
-   Flip-Flops
-   Routing Resources
-   Clock Networks

## RTL Design & Verification

-   Verilog HDL
-   Testbench Development
-   Functional Simulation
-   Waveform Analysis

## FPGA CAD Flow

-   Logic Synthesis
-   Technology Mapping
-   Placement
-   Routing
-   Bitstream Generation

## Static Timing Analysis

-   Setup Analysis
-   Hold Analysis
-   Critical Path Identification
-   Timing Constraints using SDC

## FPGA Architecture Exploration

-   EArch FPGA Architecture
-   SOFA FPGA Fabric
-   Routing Congestion Analysis
-   Resource Utilization
-   Timing Closure

## OpenFPGA Flow

-   FPGA Fabric Generation
-   Architecture Mapping
-   Netlist Generation
-   Post-Implementation Simulation

------------------------------------------------------------------------

# FPGA Architectures Explored

## EArch FPGA Architecture

The EArch architecture was explored to understand:

-   Placement algorithms
-   Routing architecture
-   Timing analysis
-   FPGA resource utilization
-   Netlist generation

## SOFA FPGA Fabric

The SOFA FPGA framework was used to implement the **RVMYTH RISC-V
Processor Core**.

Key areas explored include:

-   Custom FPGA fabric generation
-   Placement and routing
-   Timing closure
-   Resource utilization
-   Post-implementation verification

------------------------------------------------------------------------

# Reports & Outputs

The workshop generated the following implementation reports:

-   RTL Simulation Waveforms
-   Placement Reports
-   Routing Reports
-   Setup Timing Reports
-   Hold Timing Reports
-   Critical Path Reports
-   FPGA Utilization Reports
-   Power Analysis Reports
-   FPGA Netlists
-   FPGA Architecture Reports
-   Post-Implementation Simulation Results

------------------------------------------------------------------------

# Key Learning Outcomes

By completing this workshop, the following practical concepts were
gained:

-   Complete FPGA implementation flow
-   RTL-to-FPGA design methodology
-   FPGA architecture exploration
-   Open-source FPGA CAD toolchain
-   Placement and routing techniques
-   Static timing analysis and timing closure
-   FPGA resource utilization analysis
-   Power estimation
-   FPGA fabric generation using OpenFPGA
-   RISC-V processor implementation on a custom FPGA fabric

------------------------------------------------------------------------

# References

-   VLSI System Design --- https://www.vlsisystemdesign.com/ip/
-   RVMYTH RISC-V Core --- https://github.com/shivanishah269/risc-v-core
-   4-Stage RISC-V Core ---
    https://github.com/ShonTaware/RISC-V_Core_4_Stage
-   SOFA FPGA Framework --- https://github.com/lnis-uofu/SOFA
-   OpenFPGA Documentation ---
    https://openfpga.readthedocs.io/en/master/
-   VPR Documentation ---
    https://docs.verilogtorouting.org/en/latest/vpr/
-   VTR Documentation --- https://docs.verilogtorouting.org/en/latest/

------------------------------------------------------------------------

# Acknowledgements

Special thanks to:

-   **Kunal Ghosh** --- VSD Corp Pvt. Ltd.
-   **VSD Workshop Team**

------------------------------------------------------------------------

This repository serves as a comprehensive reference for the complete
FPGA implementation workflow, FPGA architecture exploration, and
hands-on experience with modern open-source FPGA CAD frameworks.
