# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :![Screenshot 2024-11-21 164637](https://github.com/user-attachments/assets/230efa29-089b-4bc1-8558-c46a4e9d6d9d)


#### Area report:![Screenshot 2024-11-21 164754](https://github.com/user-attachments/assets/b1192967-9c50-4411-bc72-a1014555ac15)


#### Power Report:![Screenshot 2024-11-21 164900](https://github.com/user-attachments/assets/7442efc8-451b-4d3c-a500-72f0a15007eb)


#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
