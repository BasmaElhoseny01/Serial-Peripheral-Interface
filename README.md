# Serial-Peripheral-Interface
SPI modules are designed using Verilog.

This project focuses on the Multi-Slave Regular Mode (as shown in Fig. 6) with SPI mode 1 (CPOL = 0, CPHA = 1 as shown in Fig. 3). [in Introduction-to-SPI-Interface.pdf attached].
-------------------------------------------------------------------------------------------------------------------------------------------------------------
It is a self-checking based project

The Data transmitted is 8 bits.
We have 3 slaves and the master select which slave to enable so other slaves are disabled.
-------------------------------------------------------------------------------------------------------------------------------------------------------------
Refer to the development testbench to find out more about the interface between the master/slave and the test bench.

------------------------------------------------------------------------------------------------------------------------------------------------------------
The main file to run is DevelopmentTB.v

------------------------------------------------------------------------------------------------------------------------------------------------------------
For more details about the code understanding and protocol refer to the details.pdf
