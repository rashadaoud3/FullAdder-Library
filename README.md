
# FullAdder Library

## Description

This repository contains a FullAdder library designed for the EDA Electric tool, offering modular and reusable components for digital logic circuit design. The library also supports LTspice simulations, providing schematic, layout, and icon cells for all included gates and the FullAdder.

The library integrates the following components:
- FullAdder: Combines Inverter, XOR, NOR, and NAND gates to implement a functional full adder.
- Inverter, XOR, NOR, NAND: Individual libraries for modular use in logic design. 

This project is ideal for designing and simulating digital logic circuits in educational and professional settings.

## Features
1. Schematic, layout, and icon cells for all components.
2. Designed for use with the EDA Electric tool for logic circuit design.
3. Supports LTspice simulations by exporting SPICE-compatible netlists from schematics.
4. Modular structure for flexibility in logic design.

## Usage
1. Open the EDA Electric tool and load the FullAdder library. 
2. Use the FullAdder or individual gates (Inverter, XOR, NOR, NAND) in your digital circuit designs. 
3. Simulate the designs using LTspice for verification.

## Usage with LTspice
Although the repository does not include pre-generated SPICE netlist files, you can use the provided schematics to perform simulations in LTspice. Follow these steps:

1. Export a Netlist:

 - Open the provided schematic files in the EDA Electric tool.
 - Generate a SPICE-compatible netlist from the schematic (refer to the EDA Electric tool's documentation for detailed steps).

2. Import into LTspice:

- Save the generated netlist as a .spi file.
- Open LTspice and load the .spi file.

3. Run the Simulation:

- Use LTspice’s simulation commands to analyze the circuit’s behavior.
- View waveforms and validate the circuit's performance.


  
