## Team Members
- **Abbass Aoun**
- **Kassem Smaily**
- **Mohammad Jouni**

---

# Logic Design Lab Final Project COE 322: Dynamic Logic-Based Switching System

This repository contains the final project for our Logic Design Lab course. The project implements a dynamic switching system where switches control lamps using digital logic circuits, state machines, and memory elements.

---

## Project Summary

This system allows users to dynamically assign switches to control different lamps based on a selected configuration mode. The design simulates how physical switches, logic gates, and flip-flops work together to achieve flexible switching behavior.

Key features:
-Real-time mapping of switches to lamps
-Support for multiple configurations
-Clocked memory using flip-flops
-Finite State Machine (FSM) for control logic

---

## Logic Design Concepts Used

-  Combinational Logic & Truth Tables  
-  Sequential Logic (JK/RS/D Flip-Flops)  
-  Finite State Machine (FSM) Design  
-  Karnaugh Maps for Boolean simplification  
-  Clocked memory and edge-triggered transitions  
-  LED/Lamp simulation

---

## Tools & Technologies

- Logic Simulator: *Logisim / Quartus / Multisim* (edit this)
- Language: *Verilog / VHDL* (if applicable)
- Platform: *Breadboard & ICs / Software Simulation* (edit this)
- Documentation: State diagrams, circuit schematics, truth tables

---

## How It Works

1. System starts in `IDLE` mode
2. User selects a configuration using input controls
3. FSM determines switch-to-lamp mapping
4. Logic gates activate lamps based on switch states
5. State is stored using edge-triggered flip-flops


