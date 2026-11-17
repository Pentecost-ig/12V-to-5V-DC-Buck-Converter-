# 12V to 5V DC Buck Converter Design Using LM2596

## Project Overview

This project focuses on the design and simulation of a DC to DC buck converter that steps down a 12V DC input to a regulated 5V DC output using the LM2596 switching voltage regulator.

The project covers circuit schematic development, component selection, PCB layout design and circuit simulation. The objective is to understand the working principle of switching regulators and apply PCB design practices to develop a compact power conversion circuit.

**Note:** This is a software-based design and simulation project. The PCB has not been physically fabricated or tested.

## Project Specifications

| Parameter | Specification |
|---|---|
| Project Type | DC to DC Buck Converter |
| Input Voltage | 12V DC |
| Output Voltage | 5V DC |
| Converter Type | Step Down (Buck) |
| Voltage Regulator | LM2596 |
| Schematic and PCB Design | KiCad |
| Circuit Simulation | LTspice |
| Hardware Implementation | Not performed |

## Components Used

The circuit design includes the following components:

- LM2596 switching voltage regulator
- Inductor
- Schottky diode
- Input capacitor
- Output capacitor
- Supporting resistors
- Input and output connectors

Component values and ratings are based on the circuit schematic and selected design requirements.

## Design Methodology

### 1. Circuit Design

Developed the buck converter schematic using the LM2596 switching regulator. Selected the supporting components required for voltage conversion, filtering and circuit operation.

### 2. Circuit Simulation

Used LTspice to simulate the converter circuit and study its electrical behaviour.

The simulation was used to examine:
- Input and output voltage behaviour
- Switching regulator operation
- Output voltage regulation
- Transient response, where simulated

### 3. PCB Design

Developed the PCB layout using KiCad, including:

- Component footprint selection
- Component placement
- Copper track routing
- Ground connections
- Input and output connector placement
- PCB layout inspection

### 4. Design Review

Reviewed the schematic and PCB layout for connectivity, component placement and routing considerations.

## Tools and Software

| Tool | Application |
|---|---|
| KiCad | Schematic design and PCB layout |
| LTspice | Circuit simulation |
| GitHub | Project documentation and version control |


## Project Limitations

This project was completed entirely using electronic design and simulation software.

- No physical PCB fabrication was performed.
- No physical component assembly was carried out.
- No hardware testing or measurement was performed.

The results represent schematic design, PCB layout and software simulation work only.

## References

- Texas Instruments LM2596 Datasheet
- KiCad Documentation
- LTspice Documentation

---

**Designed by:** Vivek

**Project:** 12V to 5V DC Buck Converter

**Tools:** KiCad | LTspice
