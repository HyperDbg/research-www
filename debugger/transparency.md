---
layout: default
title: Transparency
parent: Debugger
nav_order: 2
---

# Transparency
{: .no_toc }

HyperDbg is more transparent compared to other debugger by its nature. Generally, basing the debugger on the hypervisor layer makes HyperDbg more transparent than other debuggers. HyperDbg doesn’t use any debugging-related API, so even the operating system doesn’t have any idea that it’s being debugged! And that’s not all! HyperDbg can also hide from microarchitectural timing attacks that reveal the presence of the hypervisors. Transparency is a priority and is under active development.


## VM-exit Transparency in HyperDbg

In this short article we describe the progress on developing the transparency feature of the Hyperdbg. We have developed a statistical-based mitigation for Hyperdbg to be immunized against timing side-channel attacks targeting sub-OS intercepting entities.

[View Document](http://example.com/){: .btn .btn-blue }
