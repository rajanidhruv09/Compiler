# WLP4 Compiler

A compiler build using C++ that translates a subset of C/C++ language known as WLP4 to MIPS assemble code.

The source code for this project has not been uploaded since it was developed as part of a UWaterloo course.

## WLP4 Language
- [WLP4 Programming Language Tutorial](https://www.student.cs.uwaterloo.ca/~cs241/wlp4/WLP4tutorial.html)
- [WLP4 Programming Language Specification](https://www.student.cs.uwaterloo.ca/~cs241/wlp4/WLP4.html)

## How to use the compiler

Create a file containing WLP4 code and save it as `file_name.wlp4`. To generate the MIPS assembly code for the WLP4 code, run the command (Note this is for the linux environment) `wlp4scan < file_name.wlp4 | wlp4parse | wlp4gen`. To generate the machine code for the MIPS assembly code pipe the output of the previous command with the assembler program `asm` eg `wlp4scan < file_name.wlp4 | wlp4parse | wlp4gen | asm`. 
