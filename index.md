---
layout: default
title: Home
nav_order: 1
description: "HyperDbg's research projects and academic papers, manuals, documents."
permalink: /
---

# Welcome to HyperDbg Research Center.
{: .fs-9 }

You can find the research papers, manuals, and academic documentation here.
{: .fs-6 .fw-300 }

[Documentations](https://docs.hyperdbg.org){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View resources on GitHub](https://github.com/HyperDbg/awesome){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Debugger

HyperDbg is designed with a focus on using modern hardware technologies to provide new features to the debuggers' world. It operates on top of Windows by virtualizing an already running system using Intel VT-x and Intel PT. This debugger aims not to use any APIs and software debugging mechanisms, but instead, it uses Second Layer Page Table (a.k.a. Extended Page Table or EPT) extensively to monitor both kernel and user executions.
