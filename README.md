# RISC-V RV32I Pipelined Processor

A 5-stage pipelined RISC-V CPU (RV32I base integer set plus the M extension) implemented in Verilog and verified in Vivado 2024.2. The pipeline covers fetch, decode, execute, memory, and write-back, with hazard detection, operand forwarding, and branch resolution.

Team project for the Computer Architecture course at The American University in Cairo. This is Abdulaziz Al-Haidary's fork of the original repository by omar-leithym.

## Verification

- Directed test suites exercising 40+ instructions.
- `Program_Generator.cpp`: a C++ random-program generator that emits randomized instruction sequences to stress-test the pipeline beyond the hand-written suites.
- Real-time register and program-counter visualization on the seven-segment display for on-board debugging.

## Contributions

- **Abdulaziz Al-Haidary**: wrote the C++ random-program generator used for validation and worked on pipeline design and verification with the team.
- **omar-leithym**: original repository owner; core pipeline implementation and integration.

## Tools

Verilog, Vivado 2024.2, C++.
