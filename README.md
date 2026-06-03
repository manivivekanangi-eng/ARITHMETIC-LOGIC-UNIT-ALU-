# ARITHMETIC-LOGIC-UNIT-ALU-
COMPANY: CODTECH IT SOLUTIONS

NAME: ANANGI MANI VIVEK

INTERN ID: CTIS8564

DOMAIN: VLSI

DURATION: 6 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION:

Introduction

An Arithmetic Logic Unit (ALU) is one of the most important components in digital electronics and computer architecture. It is responsible for performing arithmetic and logical operations inside processors and digital systems. In this project, a basic 4-bit ALU was designed and simulated using VHDL language in Xilinx Vivado 2024.1. The ALU supports operations such as Addition, Subtraction, AND, OR, and NOT using a select signal.

The main objective of this task is to understand the implementation of combinational circuits using Hardware Description Language (HDL). This project also helps in learning digital logic design, simulation techniques, and FPGA-based development.

Software and Editor Used

The software used for this project is Xilinx Vivado Design Suite 2024.1, which is a professional Electronic Design Automation (EDA) tool used for FPGA and digital circuit development. Vivado provides an integrated environment for writing HDL code, simulation, synthesis, and implementation.

The VHDL code was written using the built-in editor available in Vivado. The editor supports syntax highlighting, debugging, and error detection, which makes coding easier and more efficient. Behavioral simulation was performed using the Vivado simulator, and waveform outputs were analyzed to verify the correctness of the ALU operations.

Description of the ALU Design

The designed ALU is a 4-bit combinational circuit that takes two 4-bit inputs named A and B. It also contains a 3-bit select line called sel, which determines the operation to be performed. The output of the ALU is represented by Y.

The ALU operations are listed below:

Select Signal Operation 000 Addition 001 Subtraction 010 AND 011 OR 100 NOT

A case statement was used in the VHDL program to select the required operation based on the value of the select signal. Arithmetic operations such as addition and subtraction were implemented using the IEEE NUMERIC_STD library, while logical operations were performed using standard logical operators.

The ALU continuously checks the input values and updates the output whenever there is a change in inputs or the select signal.

Testbench and Simulation

A separate testbench file was created to test the functionality of the ALU. Different input combinations and select signals were applied to verify each operation.

The simulation results obtained from Vivado confirmed that the ALU worked correctly for all operations. The waveform viewer displayed the input and output transitions with respect to simulation time.

Some observed outputs include:

Addition: 5 + 3 = 8 Subtraction: 8 - 2 = 6 AND Operation: 12 AND 10 = 8 OR Operation: 12 OR 10 = 14 NOT Operation: NOT 12 = 3

These outputs matched the expected results, proving the correctness of the design.

Applications of ALU

ALUs are widely used in many digital electronic systems and computing devices. Some important applications are:

Microprocessors and CPUs – ALUs perform all arithmetic and logical operations inside processors. Embedded Systems – Embedded controllers use ALUs for processing data and controlling devices. Digital Signal Processing – ALUs are used in DSP applications for mathematical computations. Robotics and Automation – Robots use ALUs for decision-making and sensor data processing. Communication Systems – Digital communication systems use ALUs for encoding and decoding operations. Calculators and Computing Devices – ALUs are essential for performing mathematical operations in electronic calculators and computers.

Conclusion

In this project, a 4-bit Arithmetic Logic Unit (ALU) was successfully designed and simulated using VHDL in Xilinx Vivado 2024.1. The ALU correctly performed arithmetic and logical operations such as Addition, Subtraction, AND, OR, and NOT based on the select input signal. The simulation waveform verified the proper functioning of the design.

This project provided practical knowledge about digital circuit design, VHDL programming, and FPGA simulation. It also demonstrated the importance of ALUs in modern computing systems and digital electronics applications.

#OUTPUT

