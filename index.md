---
layout: default
title: Home
nav_order: 1
description: "HyperDbg's research projects and academic papers, manuals, documents."
permalink: /
---

# Welcome to HyperDbg Academic & Research
{: .fs-9 }

You can find the research reports, documentation, manuals, and academic papers here.
{: .fs-6 .fw-300 }

[Documentation](https://docs.hyperdbg.org){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View resources on GitHub](https://github.com/HyperDbg/awesome){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Debugger (kHyperDbg)

HyperDbg Debugger is a Windows user-mode and kernel-mode debugger designed with a focus on using modern hardware technologies to provide new features to the debuggers' world. This debugger contains multiple software and hardware modules.

## Debugger Script (dslang)

Debugger Script or **dslang** is a language designed to be fast, flexible, and to satisfy the debugger's needs to examine the target debuggee and automate the debugging and analyzing tasks.

## Virtual Machine Monitor (VMM)

VMM is a HyperDbg module that operates on top of Windows by virtualizing an already running system using Intel VT-x and Intel EPT. This module aims not to use any APIs and software debugging mechanisms; instead, it uses the Second Layer Page Table (a.k.a. Extended Page Table or EPT) extensively to monitor both kernel and user executions.

## Standard VMI and Debugging Library (libhyperdbg)

The libhyperdbg provides comprehensive standard Virtual Machine Introspection (VMI) and debugging functionalities, enabling user-mode applications to perform detailed system analysis, monitor virtual machines, and debug software efficiently.

## hwdbg Chip Debugger

The hwdbg debugger chip generator is a gate-level debugging tool designed to make configurable and synthesizable hardware debuggers for white-box and black-box chip fuzzing, testing, and reverse engineering. The primary goal of hwdbg is to provide control over hardware, enabling monitoring and modification of signals down to the granular level of a single clock cycle. It is written in Chisel and Verilog.