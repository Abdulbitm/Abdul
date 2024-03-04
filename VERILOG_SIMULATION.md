# iiitb_rv32i-risc-v rv32i

# Table of contents
- [1.RISC-V RV32I](#1-RISC-V-RV32I)
 - [2.BLOCK DIAGRAM OF RISC-V RV32I](#2-BLOCK-DIAGRAM-OF-RISC-V-RV32I)
 - [3.INSTRUCTION SET OF RISC-V RV32I](#3-INSTRUCTION-SET-OF-RISC-V-RV32I)
 - [4.FUNCTIONAL SIMULATION](#4-FUNCTIONAL-SIMULATION)
    - [4.1 About iverilog and gtkwave](#41-About-iverilog-and-gtkwave)
    - [4.2 Installing iverilog and gtkwave](#42-Installing-iverilog-and-gtkwave)
    - [4.3 The output waveform](#43-The-output-waveform)
  
   ## 1. RISC-V RV32I

This project provides an insight into the working of a few important instructions of the instruction set of a Single cycle Reduced Instruction Set Computer - Five(RISC-V) Instruction Set Architecture suitable for use across wide-spectrum of Applications from low-power embedded devices to high-performance Cloud-based Server processors. The base RISC-V is a 32-bit processor with 31 general-purpose registers, so all the instructions are 32-bit long. Some Applications where the RISC-V processors have begun to make some significant threads are in Artificial intelligence and machine learning, Embedded systems, ultra-low power processing systems, etc.

## 2. BLOCK DIAGRAM OF RISC-V RV32I
![1](https://github.com/Abdulbitm/Abdul/assets/160620896/ba781b31-81bb-4003-9b93-cff8f7825d9a)

## 3. INSTRUCTION SET OF RISC-V RV32I
![2](https://github.com/Abdulbitm/Abdul/assets/160620896/9b986703-34be-4527-8558-1e2cea21f4f9)


![3](https://github.com/Abdulbitm/Abdul/assets/160620896/0b2e2308-186c-4f70-9081-54ff8b3190ca)

## 4. FUNCTIONAL SIMULATION

### 4.1 About iverilog and gtkwave
- Icarus Verilog is an implementation of the Verilog hardware description language.
- GTKWave is a fully featured GTK+ v1. 2 based wave viewer for Unix and Win32 which reads Ver Structural Verilog Compiler generated AET files as well as standard Verilog VCD/EVCD files and allows their viewing.
  
### 4.2 Installing iverilog and gtkwave

- **For Ubuntu**

 Open your terminal and type the following to install iverilog and GTKWave
 ```
 $   sudo apt get update
 $   sudo apt get install iverilog gtkwave
 ```

![install_i_verilog_gtkwave](https://github.com/Abdulbitm/Abdul/assets/160620896/60e99641-aefa-413b-9877-53aedc86faa3)

- **To clone the repository and download the netlist files for simulation, enter the following commands in your terminal.**

 ```
 $ git clone https://github.com/Abdulbitm/Abdul
 $ cd Abdul
```
![changing directory_Abdul](https://github.com/Abdulbitm/Abdul/assets/160620896/c4c22216-3de1-4337-985f-c1347a629cf1)

- **To simulate and run the Verilog code, enter the following commands in your terminal.**

  ```
$ iverilog -o hello hello.v hello_tb.v
$ ./hello

```

![running verilog code using iverilog](https://github.com/Abdulbitm/Abdul/assets/160620896/46375be6-64b8-477b-b6ee-8e389e3a064f)
