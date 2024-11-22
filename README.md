# Exp-6: Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

Synthesis RTL Schematic :


![Screenshot 2024-11-20 203924](https://github.com/user-attachments/assets/7401fa78-43f8-418e-b87b-e1829236f1c0)


Area report:

![Screenshot 2024-11-20 204012](https://github.com/user-attachments/assets/29187483-94c0-43ab-8d87-9603d26571e6)



Power Report:

![Screenshot 2024-11-20 203955](https://github.com/user-attachments/assets/675bceaa-7c69-42e9-9e4e-f7fdf49d11f1)



Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
