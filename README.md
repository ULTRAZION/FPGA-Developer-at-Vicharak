# FPGA-Developer-at-Vicharak
Job Title: FPGA Developer: Design an FPGA-based I²C address translator to allow a single device’s I²C address to be dynamically remapped, enabling it to coexist with other devices that may have the same default address.
Task Description:

You are required to implement an FPGA module that:

●       Acts as a I2c slave for bus master and master for the target device.

●       Translates the address of one target device at a time and keeps the data intact.

●       Handles bidirectional read/write operations correctly.

Requirements:

●       Maintain standard I²C timing (100 kHz / 400 kHz).

●       Use FPGA-friendly logic: FSMs, counters, shift registers.

●       Simulate functionality using at least two devices, translating only one device’s address at a time.



Deliverables
Note - All these deliverables are non-negotiable. Upload these to github.



1. Verilog/VHDL module implementing the I²C address translator. 

2. Testbench demonstrating correct operation for one device at a time. 

3. Simulation on EDA Playground showing functional verification. https://edaplayground.com/  ( make the playground as public (any one with the link can view)

4. Resource report from FPGA software of your choice (utilization, timing summary,etc). 

5. Brief documentation explaining:
○       Architecture overview

○       FSM/logic explanation

○       How address translation is implemented

○       Design Challenges faced 


Evaluation Criteria
●       Correct I²C communication and address translation

●       Modular and clean FPGA design

●       Proper synchronous design practices

●       Quality of simulation and documentation

●       Bonus: runtime-configurable address mapping or support for multi-byte transactions


Run your simulation over here: https://edaplayground.com/, and add the link of your simulation in the field given below.

Do not use AI tool to complete the code submission, we have a special AI detection tool which reviews the code for 10+ different AI models and we will not revert back if your code has more than 20% of AI generated content.

The duration of the task is 15 days. Make a private github repository, and add this username in collaborator, "recruit-vicharak"

If you have any queries, please feel free to contact us on join-the-team@vicharak.in

Once you complete the task, share the link of your github repository in the response field below:
