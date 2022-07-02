---
layout: default
title: Kernel Debugger Design
parent: Debugger
nav_order: 1
---

# Kernel Debugger Design
{: .no_toc }

This page provides different articles on the design details of each version of the HyperDbg Debugger.
{: .fs-6 .fw-300 }

## Edition 1 (version 0.1)
{: .no_toc .text-delta }

The kernel-mode debugger of HyperDbg is called "kHyperDbg". Unlike all the other software debuggers like WinDbg and GDB, HyperDbg is not a ring 0 (kernel) debugger. It uses ring -1 for its debugging purpose. Although, Using ring -1 (Hypervisor) as the base of the debugger has its own benefits, so many considerations are required to be noted for the implementation. In this report we present the design of HyperDbg Kernel Debugger.

