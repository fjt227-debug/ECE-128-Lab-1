# ECE-128-Lab-1
The purpose of this lab was to design and implement an 8-to-1 Multiplexer. This was accomplished through writing complete Verilog code using Structural, Behavioral, and Dataflow models, and by developing the testbench and constraint files necessary for programming the FPGA to function as an 8-to-1 Multiplexer. A multiplexer is a circuit that uses combinational logic. It has multiple input lines with a single output. Select lines determine the input that is passed through to the output. In the context of our 8-to-1 multiplexer, there are 8 inputs (I0, I1, I2, I3, I4, I5, I6, and  I7), 1 output (O), and 3 select lines (S0, S1, and S2). Multiplexers are commonly used to control data and optimize resource usage, by allowing multiple inputs to share a singular output wire.
Instructions for Simulation and FPGA implementation:
1.) In the constraint add the Basys3 file (constraint file)
2.) Compile project: Create 3 different .vfiles and copy the Structural, Behavioral, and Dataflow codes
3.) Run these steps
4.) Generate Bitstream
5.) Copy the testbench to test code before programming the FPGA board
6.) Program the board
