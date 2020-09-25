# Pipelined-CSM-Architectures
Modified architectures CSM_2B,  CSM_4B, CSM_6B, and CSM_8B, by inserting pipelined registers after each block to convert the combinational path to a critical path

Architecture #1: CSM_2B:

Inserted the registers to create a 12-stage pipelined core

Architecture #2: CSM_4B

Inserted the registers to create a 6-stage pipelined core

Architecture #3: CSM_6B

Inserted the registers to create a 4-stage pipelined core

Architecture #4: CSM_8B

Inserted the registers to create a 3-stage pipelined core


Used Matlab to create input/output test vector files for the design.

Created a testbench with 4 configurations to test each architecture using your I/O files

Test the largest (positive) numbers in the range

Tested the smallest (negative) numbers in the range

Tested mixed inputs (positive and negative numbers)

Tested from both sides of zero

Tested the zero inputs

Created a schematic for each configuration using the DataFlow feature in ModelSim
