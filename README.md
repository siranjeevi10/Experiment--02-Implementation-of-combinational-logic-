## Name: Siranjeevi.S
## Reg: 23012822


# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 A combinational circuit is a circuit in which the output depends on the present combination of inputs. Combinational circuits are made up of logic gates. The output of each logic gate is determined by its logic function. Combinational circuits can be made using various logic gates, such as AND gates, OR gates, and NOT gates.


## Procedure:
1. Create a New Project: Open Quartus and create a new project by selecting "File" > "New Project Wizard." Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA)

2. Create a New Design File: Once the project is created, right-click on the project name in the Project Navigator and select "Add New File." "Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description language.

3. Write the Combinational Logic Code: Open the newly created Verilog or VHDL file and write the code for your combinational logic.

4. Compile the Project: To compile the project, click on "Processing" > "Start Compilation" in the menu. "Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device.

5. Analyze and Fix Errors: If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window. Review and fix any issues in your code if necessary. "View the RTL diagram.

6. Verification: Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF". Once Waveform is created Right Click on the Input/Output Panel > Insert Node or Bus" Click on Nade Finder >

Click On "List" > Select All. Give the Input Combinations according to the Truth Table and then simulate the Output Waveform..
## Program:
![Screenshot 2023-12-31 072202](https://github.com/siranjeevi10/Experiment--02-Implementation-of-combinational-logic-/assets/152168132/fb54fe8e-9fdb-471e-b5e3-3cd4986ff9ba)

  
## RTL Realisation:
![Screenshot 2023-12-31 072254](https://github.com/siranjeevi10/Experiment--02-Implementation-of-combinational-logic-/assets/152168132/927b6f63-6160-410d-b7fc-59cc47d39db3)



## Truth tabel:
![Screenshot 2023-12-31 072331](https://github.com/siranjeevi10/Experiment--02-Implementation-of-combinational-logic-/assets/152168132/e6b80fc6-9d84-4677-b656-b50725424f30)



## Timing Diagram:
![Screenshot 2023-12-31 072419](https://github.com/siranjeevi10/Experiment--02-Implementation-of-combinational-logic-/assets/152168132/c37713d2-4c2a-427b-a8d4-7adc29fb4116)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
