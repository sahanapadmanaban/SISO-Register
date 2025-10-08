# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

Step 1: Apply the first data bit serially at the input terminal of the first flip-flop.

Step 2: On the first clock pulse, the input bit is stored in the first flip-flop.

Step 3: Apply the next data bit and, with the next clock pulse, shift the previous bit into the second flip-flop.

Step 4: Continue applying input bits, and with each clock pulse, all stored bits shift one position to the right.

Step 5: After all bits are entered, continue giving clock pulses to shift data out serially from the last flip-flop.

Step 6: The output appears serially in the same order as the input but delayed by the number of stages in the register.


**PROGRAM**

Developed by:P.SAHANA RegisterNumber:25010400

<img width="1164" height="516" alt="{37A90596-B658-49E8-A32E-5DCDD0EB4509}" src="https://github.com/user-attachments/assets/eb2a9e0f-89cb-4a77-8318-40aca23585c6" />


**RTL LOGIC FOR SISO Shift Register**

<img width="613" height="320" alt="{6B1FC81B-86BD-418C-877F-303652803719}" src="https://github.com/user-attachments/assets/473d759a-824e-4236-a2da-4935077ea8a4" />

**TIMING DIGRAMS FOR SISO Shift Register**

<img width="1028" height="155" alt="image" src="https://github.com/user-attachments/assets/43aeade0-7d87-4cd6-9a3e-0369e7791c88" />

**RESULTS**
 Thus SISO Shift Register using verilog and validating their functionality using their functional tables has successful execution of the program.
