# Final
Contains the final code for BPU

Author:Ram Srivathsa Sankar

Mentor:Rahul Bodduna

The 'src' folder contains the final files for the btb(parametrized), branch predictor(with shadow registers) and bpu that can be used for the c-class processor.

Results: Without the use of shadow registers, the processor executes at 94,500 Dhrystones/second. With the shadow registers, the processor executes at 97,500 Dhrystones/second.

The branch predictor occupies 885 LUTs on an Artix 7 board and can operate at a maximum frequency of 256MHz.
For a 4-way set associative BTB with 16 entries per way and a 17 registers deep fully associative unconditional branch stack, the BPU occupies 1.6k LUTs on an Artix 7 board and can operate at a maximum frequency of 135 MHz.
