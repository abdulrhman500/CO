# Simple Computer 
A computer to do a simulation for a
memory system and an arithmetic/logic unit and a group of registers


## Description

All components are linked 
through a common bus that has 3 control select lines S2, S1 and S0.

* The memory (RAM) should have 128 addresses (words). Each word is 16-bits.
* control unit
* Users are able to read and write to the memory.
* The Address Register (AR) output should be linked to the address lines of the memory 
* The memory’s input and output lines are connected to the common bus.
* The available registers are:
     * DR
     * TR
     * AR
     *AC (Accumulator Register)
     * PC
* Each register has a load enable flag to control whether the data available from the bus, will update its content or not.
