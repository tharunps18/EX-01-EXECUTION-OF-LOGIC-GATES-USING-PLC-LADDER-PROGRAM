# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME : THARUN P S
 # REGISTER NUMBER : 212224110055
 # DEPARTMENT : BE.CSE(IOT)
 # YEAR : 3
 # DATE : 26/10/2026

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:
## AND GATE:
 <img width="327" height="250" alt="image" src="https://github.com/user-attachments/assets/5cf9dd15-a6e2-4d1e-880d-d113ef1f2d0d" />
 
## OR GATE:
 <img width="324" height="254" alt="image" src="https://github.com/user-attachments/assets/1e6935d4-47f8-4452-aecb-05fe4197dac7" />
 
## NOT GATE:
 <img width="214" height="159" alt="image" src="https://github.com/user-attachments/assets/8321a8ed-43b3-4e1b-88de-a151e3f22772" />
 
## NAND GATE:
 <img width="333" height="250" alt="image" src="https://github.com/user-attachments/assets/ebaa3105-cfe5-474e-b809-6c83415a019a" />
 
## NOR GATE:
 <img width="330" height="249" alt="image" src="https://github.com/user-attachments/assets/7fc0c378-9e21-42bb-bd6a-e950b9323c17" />
 
## XOR GATE:
 <img width="326" height="248" alt="image" src="https://github.com/user-attachments/assets/99d7a304-789c-4570-91a9-685e225d0996" />
 
# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 
<img width="2560" height="1600" alt="Screenshot 2026-10-26 095722" src="https://github.com/user-attachments/assets/5eb3d636-0de2-4b91-bd84-5a5691dddc37" />

<img width="2560" height="1600" alt="Screenshot 2026-10-26 095738" src="https://github.com/user-attachments/assets/9db2ce9a-5537-4acb-92cb-24a175eec222" />

<img width="2560" height="1600" alt="Screenshot 2026-10-26 095750" src="https://github.com/user-attachments/assets/e9121d2a-0725-4fb9-aef4-cf3de62ef2ca" />

<img width="2560" height="1600" alt="Screenshot 2026-10-26 095807" src="https://github.com/user-attachments/assets/eaf0bc1a-b649-4664-b33d-9ce0c6a2e6b9" />

<img width="2560" height="1600" alt="Screenshot 2026-10-26 102038" src="https://github.com/user-attachments/assets/e8815769-c16a-4315-8f26-0cb74bed6d5e" />

<img width="2560" height="1600" alt="Screenshot 2026-10-26 102107" src="https://github.com/user-attachments/assets/e4316811-0435-4617-8829-cc5c82a97327" />

<img width="2560" height="1600" alt="Screenshot 2026-10-26 102126" src="https://github.com/user-attachments/assets/f96b0426-cec9-4956-aea7-da8dc18c2e11" />

<img width="2560" height="1600" alt="Screenshot 2026-10-26 102157" src="https://github.com/user-attachments/assets/145fb8db-4247-4be4-8c90-00374d7819c3" />


# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
