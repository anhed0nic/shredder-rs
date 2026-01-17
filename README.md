# Shredder-RS

A polymorphic mutation engine for x86_64 binaries.

## Overview
Shredder-RS implements instruction-level shredding to defeat static analysis. By breaking the linear flow of the code and injecting randomized junk nodes, it forces disassemblers to follow a complex graph of JMP-linked instructions.

## Key Features
- **Context-Aware Mutation:** Preserves EFLAGS and volatile registers.
- **Non-Linear Layout:** Randomized physical instruction placement.
- **PE Support:** Automated section injection and EntryPoint hijacking.

## Documentation
For deep technical details, see [ARCHITECTURE.md](./ARCHITECTURE.md).
