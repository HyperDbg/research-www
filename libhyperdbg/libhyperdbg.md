---
layout: default
title: VMI and Debugging Libraries (libhyperdbg)
nav_order: 6
has_children: false
permalink: /libhyperdbg
---

# Standard VMI and Debugging Library (libhyperdbg)

HyperDbg libraries
{: .fs-6 .fw-300 }

## Overview
`libhyperdbg` is a user-mode library for HyperDbg that facilitates Virtual Machine Introspection (VMI) and advanced debugging tasks. It provides an array of functions for managing the Virtual Machine Monitor (VMM), memory, registers, breakpoints, and debugger connections.

## Function Categories

Some of these functionalities include:

### VMM Control
- Load, unload, install, and uninstall the VMM.
- Detect VMX support.

### Debugger Control
- Execute commands.
- Manage local and remote debugger connections.

### Memory Management
- Read and write memory.

### Register Management
- Read and write registers.
- Display register values.

### Breakpoints and Execution Control
- Set breakpoints.
- Control debuggee execution (continue, pause).

### Process Management
- Start processes with or without arguments.

### Assembler
- Assemble code and determine instruction lengths.

## Usage
To use `libhyperdbg`, integrate it into your user-mode application and utilize its functions for advanced debugging and VMI tasks programmatically.

For more details, visit the [HyperDbg SDK Documentation](https://docs.hyperdbg.org/using-hyperdbg/sdk).