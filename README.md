# Assembly-Language

Title: Assembly Language Program

Description:
This is a simple Assembly language program that demonstrates some basic operations on the x86 architecture. The program is written in the 32-bit flat memory model and uses the stdcall calling convention. It declares a stack size of 4096 and uses the Windows API function "ExitProcess" to terminate the program.

The program performs the following operations:

    Loads a 32-bit value into the EAX register
    Loads a 16-bit value into the AX register
    Copies the lower byte of AL to BL
    Copies the higher byte of AX to BL
    Adds 10h to the AL register
    Clears the AL register by subtracting itself
    Loads 98h into AL and adds 89h to it
