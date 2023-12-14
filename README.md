# Operating Systems Engineering: JOS Labs 1-3

This repository contains my work on Labs 1 to 3 of the Operating Systems Engineering course, focused on building key components of the JOS operating system. JOS is a simplified, Unix-like operating system implemented in an exokernel style, designed to provide a deep understanding of fundamental OS concepts.

## Overview

The course is structured to give hands-on experience in building an operating system from scratch. It involves detailed study and implementation of core operating system concepts, with an emphasis on understanding the complexity and interactions of various OS components.

### Lab 1: Booting

**Objective**: Understand the booting process of an x86-based system. The lab involves writing the initial bootstrapping code for JOS, enabling it to start up and transition from real to protected mode.

**Key Concepts**: BIOS, bootloader, real vs. protected mode, memory layout.

### Lab 2: Memory Management

**Objective**: Implement memory management in JOS, including physical and virtual memory allocation, page management, and handling of memory-mapped I/O.

**Key Concepts**: Paging, page tables, memory allocation, segmentation.

### Lab 3: User Environments

**Objective**: Establish the groundwork for supporting user-level processes. This includes setting up an environment to run user programs and handling system calls and user-level exceptions.

**Key Concepts**: System calls, user-space and kernel-space, exception handling, context switching.

## Development Environment

All labs are developed and tested using the QEMU machine emulator, simulating a standard x86-based personal computer. This setup provides a controlled environment for OS development and debugging.

## Collaboration and Contribution

These labs were completed individually as part of the course curriculum. However, collaboration in the form of ideas, bug reports, and discussions is welcome.
