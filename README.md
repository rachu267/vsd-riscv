#VSD-RISCV
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The program is based on the RISC-V architecture and uses open-source tools for VLSI chip design and RISC-V.

#Basic Details
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Name: Rachagond Doddashivannavar

College: Vidyavardhaka College of Engineering

Email ID: rachagonddoddashivannavar@gmail.com

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


#Task 1:Review lab videos on C programming and RISC-V architecture. Perform the task of compiling C code using both the GCC compiler and the RISC-V compiler, demonstrating an understanding of the compilation process


Task is to refer to C based and RISCV based lab videos and execute the task of compiling the C code using gcc and riscv compiler
C and RISC-V Based Labs

This repository demonstrates the processes involved in compiling C programs and generating assembly code using both a standard GCC compiler and a RISC-V GCC compiler. It includes comprehensive steps and explanations to guide users through each stage of the compilation and debugging workflow.

C Language-Based Lab

Steps to Compile a .c File on Your Machine:

1.Open the bash terminal and navigate to the directory where you want to create your file.
2.Use the following command to create and edit a new .c file:
  gedit filename.c

to check the output command
 ./a.out

 ![VirtualBox_vsd3_22_03_2025_22_45_28](https://github.com/user-attachments/assets/5728c6cf-335b-4246-945e-d3c8b53aacbe)

 ->commands
 ![VirtualBox_vsd4_22_03_2025_22_46_59](https://github.com/user-attachments/assets/92eea395-9bab-420f-86d8-9867b0dd8fd3)

 ![VirtualBox_vsd2_22_03_2025_22_42_03](https://github.com/user-attachments/assets/2f964922-c205-453e-b5c4-51a0fc8a97d1)



 #Task: Compile and Analyze C Program with RISC-V GCC/SPIKE under Different Optimization Flags (-O1 and -Ofast)

 #Overview:
 --------------------------------
The SPIKE simulator is a RISC-V instruction set simulator that helps in simulating and testing RISC-V programs in a controlled environment. It is commonly used in scenarios where you want to analyze, test, and debug programs on a RISC-V architecture without having access to actual hardware. SPIKE works by emulating the behavior of RISC-V processors and can be used to simulate the execution of compiled RISC-V code, making it a useful tool for developers and researchers working with RISC-V.

#Key Features of SPIKE:
------------------------
RISC-V ISA Emulator: SPIKE simulates a processor based on the RISC-V architecture. It supports different versions of the RISC-V ISA (Instruction Set Architecture) and can emulate the execution of RISC-V machine code.

Simulation of RISC-V Programs: Once you have compiled your RISC-V program (e.g., using a cross-compiler for RISC-V like RISC-V GCC), you can run that binary in SPIKE to simulate how the program would behave on a RISC-V processor.

Debugging and Tracing: SPIKE allows you to perform detailed debugging of the execution of RISC-V programs. You can trace the program’s execution, inspect register values, and monitor memory operations. This feature makes it a valuable tool for understanding how code performs at the assembly and machine code level.

Performance Evaluation: By running your program under different compiler optimizations, such as -O1 and -Ofast, SPIKE can be used to compare the performance of the program under different settings. You can observe how optimizations affect execution time, memory usage, and CPU cycles.

Integration with Other Tools: SPIKE can be used with other RISC-V development tools, like debuggers or performance profilers, to get a more in-depth analysis of the code.
![program](https://github.com/user-attachments/assets/427dba95-f513-424f-bfd4-355742ed68de)

#How SPIKE Simulation Works:
-------------------------------------------------------------------------------------------------------------------------------------------
Setup: You begin by setting up the RISC-V environment, which includes installing SPIKE, the RISC-V GCC toolchain, and any other necessary utilities.

Compilation: You write a simple C program (or any program) and compile it using the RISC-V toolchain. When compiling, you can specify optimization flags like -O1 or -Ofast to see how different levels of optimization affect the compiled code.

Running the Program: After compiling your program, you can run it in the SPIKE simulator. The simulation will interpret each instruction of your compiled RISC-V code and allow you to observe the behavior and performance.

Object Dump Analysis: When you compile a program with different optimization flags, you can also generate object dumps (like .o files) that contain the low-level assembly instructions and memory layout of your program. These dumps can be analyzed to see how different optimizations impact the machine-level code.

Performance Metrics: By running the program on SPIKE, you can also gather performance metrics, such as how long the program takes to execute under different optimization flags and how the program uses CPU cycles and memory.

![-Ofast](https://github.com/user-attachments/assets/303836e4-1320-4de6-a3dd-91dee9c173f4)

#Optimization Flags in SPIKE:
---------------------------------------------------------------------------------------------------------------------
When compiling your program, you can use optimization flags like -O1 and -Ofast to see how they affect the performance:

-O1 Optimization: This level of optimization focuses on balancing performance and compilation time. It may improve performance without significantly increasing compilation time.

-Ofast Optimization: This flag enables aggressive optimizations that prioritize performance over everything else, sometimes sacrificing correctness or strict compliance with the C standard. It often leads to faster code at the cost of potentially more aggressive assumptions about the hardware.

![riscv commands](https://github.com/user-attachments/assets/20fba24e-2826-4b02-9850-2917570566fe)

![out](https://github.com/user-attachments/assets/adb2eab8-7110-4cd3-9bc9-30261733af46)






