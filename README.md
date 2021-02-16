# Playground

Tried linking the const array with pragma at first but always failed and the array ended up either in the com section when uninitialized or the rodata when initialized. 
So for the sake of time I updated the def in the .c file to be attribute based without resorting to including the absolute address in the .c  
