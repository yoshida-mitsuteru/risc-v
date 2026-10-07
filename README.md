# RISC-V

A compact, implementation-oriented reference for RISC-V processor
microarchitecture, from the RV32I instruction set and RTL implementation to
software execution and hardware validation.

The initial target is a 32-bit processor based on RV32I, implemented in
SystemVerilog with sufficient system support to execute compiled C programs
and a small RTOS.

## Scope

The material will cover processor implementation and verification, including:

- RV32I base integer instruction set
- 32-bit datapath and register file
- Pipelined microarchitecture
- Data forwarding and hazard handling
- Instruction and data memory interfaces
- Machine-mode CSR support
- Exceptions and traps
- Timer and interrupt handling
- Self-checking verification
- Execution of compiled C programs
- Small RTOS execution
- Synthesis and FPGA validation

The implementation will also document architectural decisions and trade-offs
such as pipeline structure, hazard handling, memory-interface behavior, and
performance versus implementation cost.

Future extensions may include the RV32M extension, cache integration, and
connection to a larger SoC interconnect.

## Repository Status

Implementation is planned.

Architecture notes, source code, verification results, and implementation
results will be added incrementally as the project progresses.
