---
layout: default
title: Home
nav_order: 1
description: "HyperDbg's research projects and academic papers, manuals, documents."
permalink: /
---

# Welcome to HyperDbg Research.
{: .fs-9 }

You can find the research papers, manuals, and academic documentation here.
{: .fs-6 .fw-300 }

[Documentation](https://docs.hyperdbg.org){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View resources on GitHub](https://github.com/HyperDbg/awesome){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Debugger

HyperDbg Debugger is a Windows debugger designed with a focus on using modern hardware technologies to provide new features to the debuggers' world. This debugger contains multiple software and hardware modules.

## Debugger Script

Debugger Script is a language designed to be fast, flexible, and to satisfy the debugger's needs to examine the target debuggee and automate the debugging and analyzing tasks.

## Virtual Machine Monitor (VMM)

VMM is a HyperDbg module that operates on top of Windows by virtualizing an already running system using Intel VT-x and Intel PT. This module aims not to use any APIs and software debugging mechanisms; instead, it uses Second Layer Page Table (a.k.a. Extended Page Table or EPT) extensively to monitor both kernel and user executions.

## Clkr Circuit

Clkr (Clocker) Circuit is an HDL module integrated into the HyperDbg Debugger to bring the power of digital circuit debugging to the HyperDbg. (This module is under development and not in a working state yet!)