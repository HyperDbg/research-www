---
layout: default
title: Debugger Script (dslang)
nav_order: 4
has_children: true
permalink: /dslang
---

# Debugger Script (DS)

Debugger Script
{: .fs-6 .fw-300 }

## Overview
Debugger Script Language (dslang) is a powerful scripting language used within the HyperDbg debugger to automate debugging tasks, perform evaluations, and manipulate variables. This guide provides a detailed overview of the dsLang syntax, structure, and capabilities.

## Scripting Language Components

### Assumptions & Evaluations
dslang scripts operate under specific assumptions:
- Evaluation of expressions follows typical precedence rules.
- Supports basic arithmetic, logical operations, and bitwise operations.

### Variables & Assignments
Variables in dslang can be declared and assigned values easily:
- **Declaration**: Variables are implicitly declared upon first assignment.
- **Types**: The language is type-aware, allowing for different data types including integers, strings, and more.
- **Assignment**: Use the `=` operator for assignment.

### Casting & Type-awareness
dslang supports explicit type casting to ensure proper operations on different data types:
- Cast operations can be performed using specific functions.

### Conditionals & Loops
Control flow in dslang is managed using standard conditional statements and loops:
- **Conditionals**: `if`, `else if`, and `else` statements.
- **Loops**: `while` and `for` loops for iteration.

### Functions in dslang
dslang provides a set of built-in functions categorized under various modules:
- **Debugger Functions**: Control debugger operations like pausing.
- **Events Functions**: Manage event handling and manipulation.
- **Export Functions**: Functions like `print` and `printf` for output.
- **Interlocked Functions**: Atomic operations for concurrency control.
- **Memory Functions**: Manipulate and check memory addresses.
- **Disassembler Functions**: Disassemble instructions.
- **Spinlock Functions**: Manage spinlocks for synchronization.
- **String Functions**: Handle string operations.

## Examples
dslang scripts can be used to perform various debugging tasks:
- **View system state**: Access and display registers, memory, and variables.
- **Change system state**: Modify registers, memory, and variables.
- **Trace function calls**: Monitor and trace function calls.
- **Conditional breakpoints**: Set breakpoints based on specific conditions.
- **Patch execution flow**: Alter the normal sequence of execution.
- **Access shared variables**: Manage variables across different cores.
- **Count events**: Track the number of specific events.

For more detailed examples and comprehensive documentation, visit the [HyperDbg Documentation](https://docs.hyperdbg.org/commands/scripting-language).

