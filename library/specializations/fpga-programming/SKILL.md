---
name: specialization-fpga-programming
description: "FPGA (Field-Programmable Gate Array) Programming and Hardware Description is a specialized discipline focused on designing, implementing, and optimizing digital circuits using reconfigurable hardware. This specialization encompasses the use of Hardware Description Languages (HDLs) such as VHDL,…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: fpga-programming
  process-count: 25
---

# specialization-fpga-programming

## Overview

FPGA (Field-Programmable Gate Array) Programming and Hardware Description is a specialized discipline focused on designing, implementing, and optimizing digital circuits using reconfigurable hardware. This specialization encompasses the use of Hardware Description Languages (HDLs) such as VHDL, Verilog, and SystemVerilog to describe digital systems at various levels of abstraction, from behavioral models to synthesizable Register Transfer Level (RTL) designs.

## Available Processes (25)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/fpga-programming/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `axi-interface-design` (`specializations/fpga-programming/axi-interface-design`) | AXI Interface Design and Implementation - Design AXI4, AXI4-Lite, and AXI4-Stream interfaces. Implement |
| `cdc-design` (`specializations/fpga-programming/cdc-design`) | Clock Domain Crossing (CDC) Design - Design and verify safe clock domain crossing circuits. Implement |
| `clock-network-design` (`specializations/fpga-programming/clock-network-design`) | Clock Network Design and Constraints - Design clock distribution networks using global and regional |
| `constrained-random-verification` (`specializations/fpga-programming/constrained-random-verification`) | Constrained Random Verification (CRV) - Develop constrained random testbenches using SystemVerilog |
| `design-for-testability` (`specializations/fpga-programming/design-for-testability`) | Design for Testability (DFT) - Implement JTAG boundary scan, BIST (Built-In Self Test), and production |
| `fpga-on-chip-debugging` (`specializations/fpga-programming/fpga-on-chip-debugging`) | FPGA On-Chip Debugging - Set up and use integrated logic analyzers (ILA), virtual I/O (VIO), and debug |
| `fsm-design` (`specializations/fpga-programming/fsm-design`) | Finite State Machine (FSM) Design - Design and implement finite state machines using one-hot, binary, |
| `functional-simulation` (`specializations/fpga-programming/functional-simulation`) | Functional Simulation and Debug - Execute functional simulations to verify RTL behavior against |
| `hardware-software-codesign` (`specializations/fpga-programming/hardware-software-codesign`) | Hardware-Software Co-Design - Partition algorithms between PS (Processing System) and PL (Programmable Logic). |
| `hls-development` (`specializations/fpga-programming/hls-development`) | High-Level Synthesis Development - Develop hardware accelerators using C/C++ with HLS tools. Optimize |
| `ip-core-integration` (`specializations/fpga-programming/ip-core-integration`) | IP Core Integration - Integrate vendor IP cores and custom IP blocks into designs. Configure IP |
| `memory-interface-design` (`specializations/fpga-programming/memory-interface-design`) | Memory Interface Design - Design high-performance memory interfaces including DDR3/DDR4 controllers, |
| `pipeline-architecture` (`specializations/fpga-programming/pipeline-architecture`) | Pipeline Architecture Implementation - Design and implement pipelined architectures to achieve high |
| `place-and-route` (`specializations/fpga-programming/place-and-route`) | Place and Route Optimization - Optimize placement and routing to achieve timing closure and minimize |
| `power-analysis-optimization` (`specializations/fpga-programming/power-analysis-optimization`) | Power Analysis and Optimization - Analyze and optimize FPGA power consumption. Apply clock gating, power |
| `reset-strategy` (`specializations/fpga-programming/reset-strategy`) | Reset Strategy Design - Design robust reset distribution and synchronization for single and multi-clock |
| `rtl-module-architecture` (`specializations/fpga-programming/rtl-module-architecture`) | RTL Module Architecture Design - Design and document the architecture for RTL modules including interface |
| `sva-development` (`specializations/fpga-programming/sva-development`) | SystemVerilog Assertion (SVA) Development - Implement concurrent and immediate assertions to verify |
| `synthesis-optimization` (`specializations/fpga-programming/synthesis-optimization`) | Synthesis Optimization - Optimize RTL for synthesis to meet area, timing, and power goals. Apply |
| `testbench-development` (`specializations/fpga-programming/testbench-development`) | Testbench Development - Create comprehensive testbenches for RTL verification including stimulus |
| `timing-closure` (`specializations/fpga-programming/timing-closure`) | Timing Closure Strategies - Achieve timing closure through systematic analysis and optimization |
| `timing-constraints` (`specializations/fpga-programming/timing-constraints`) | Timing Constraint Development - Develop comprehensive timing constraints (SDC/XDC) including clock |
| `uvm-testbench` (`specializations/fpga-programming/uvm-testbench`) | UVM Testbench Architecture - Design and implement Universal Verification Methodology (UVM) testbenches |
| `verilog-systemverilog-design` (`specializations/fpga-programming/verilog-systemverilog-design`) | Verilog/SystemVerilog Design Implementation - Implement digital designs using Verilog or SystemVerilog |
| `vhdl-module-development` (`specializations/fpga-programming/vhdl-module-development`) | VHDL Module Development - Develop synthesizable VHDL modules following IEEE 1076 standards and industry |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `fpga-programming` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
