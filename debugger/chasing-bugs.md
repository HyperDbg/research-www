---
layout: default
title: Chasing Bugs
parent: Debugger (kHyperDbg)
nav_order: 2
---

# Chasing Bugs with/in Hypervisors
{: .no_toc }

This article discusses HyperDbg and its associated methods for compromising hypervisors, which were originally presented at Zer0Con 2023 ([zer0con.org](https://zer0con.org)).

## Abstract

Hypervisors are an indispensable component of contemporary software systems. While the primary purpose of hypervisors is to virtualize the system resources. There are various other applications for hypervisors besides their conventional use, and our focus lies in employing them for security and reverse engineering purposes; thus, this presentation is divided into two parts. The first part is about how hypervisors and solutions derived from hypervisors can help us in finding bugs in kernel-mode and user-mode routines as well as discussing the possibilities of using hypervisor debuggers in reverse engineering. The second part is about finding different types of bugs within the hypervisors (type 1 and type 2).

The study involves using various bug-finding techniques, including static analysis, dynamic analysis, and finding attack vectors, to identify vulnerabilities in both types of hypervisors. The presentation also highlights the importance of bug finding in hypervisors and the potential consequences of leaving vulnerabilities unaddressed. The findings can inform developers and security professionals in their efforts to improve the security of hypervisors and mitigate the risks associated with virtualization.

[View Document](https://research.hyperdbg.org/assets/documents/chasing-bugs-with-in-hypervisors.pdf){: .btn .btn-blue }
