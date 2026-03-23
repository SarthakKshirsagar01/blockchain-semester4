# Blockchain Semester 4 — Learning Journal

## Day 2 — StudentRegistry

### What it does
An on-chain registry that maps student wallet addresses
to their name and roll number. Only the contract owner
can register new students.

### What I learned
- How mappings store key-value data on-chain
- How events log state changes for the frontend
- How modifiers enforce access control

### How to run
1. Open StudentRegistry.sol in Remix IDE
2. Compile with Solidity ^0.8.0
3. Deploy to Remix VM and test registerStudent()
