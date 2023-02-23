# Kathleen16-Mk.1
Reproduction of the 16-bit processor called Kathleen16 Mk.1 in honor of Kathleen Booth, author of the first assembly language.

The main goal of this project is to realize 4 distinct circuits : 
  - the Expander 10↑16 
  - the Arithmetic and Logical Unit (ALU)
  - the Register bench
  - the Instruction Fetch Unit (IFU)
  
Once it's done, we translate an algorithm written in assembly language (MIPS) into a series of 0 and 1 we can execute with the circuits created earlier.

Additionnally, we re-wrote the pseudo-instructions not supported by the processor (like "and" , "not", "or") in "native" instructions understandable for the Kathleeen 16.

Warning : The ".circ" file can only be opened with the software Logisim.
