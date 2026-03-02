# Shane Nelson 
![This is me](EU2A0146.jpeg)

**Computer Science & Political Science — University of Washington**  
Seattle, WA · [GitHub](https://github.com/shanenelson1117) · [Email](mailto:shanenelson1117@gmail.com)

---

## About

I am a senior at UW interested in systems programming at every level of the stack — from hardware to operating systems to user-space runtimes. I enjoy understanding how things work at the level beneath the abstraction, and building things that require that understanding.

Outside of computing I play hockey, cook, and watch too much Brooklyn Nine-Nine.

---

## Highlighted Projects

### Out-of-Order RISC-V CPU
*SystemVerilog / Hardware Design*

A cycle-accurate simulation of an out-of-order superscalar RISC-V processor. Implements Tomasulo's algorithm with a reorder buffer, reservation stations, a load-store queue, branch prediction with a global history shift register and branch prediction buffer, a return address stack, and a CSR file with privilege levels and trap handling.

---


### Java Subset Compiler
*Compiler Design*

A compiler for a subset of Java, including lexing, parsing, semantic analysis, and code generation. Covers the full translation pipeline from source to machine code.

---

### M:N User-Level Thread Library *(in progress)*
*C / x86-64 Assembly / Systems Programming*

A user-level M:N threading library written in C. Implements green threads with work-stealing scheduling across multiple kernel threads, signal-based preemption, and synchronization primitives (mutex, condvar). Green thread stacks are allocated via mmap with guard pages for overflow detection. Context switching is implemented in x86-64 assembly saving and restoring callee-saved registers per the SysV ABI.

---

## Upcoming Projects

### Operating System on ARMv8 (i.MX 8X) *(Future Capstone)
*C / ARM Assembly / Systems Programming*

A fairly complete operating system for NXP's ARMv8-based i.MX 8X hardware built over the course of a semester. Based on the Barrelfish multikernel originally developed at ETH Zurich in collaboration with Microsoft Research. Covers process management, virtual memory, inter-process communication, and device drivers on real silicon.

---

### Distributed Key-Value Store
*Distributed Systems*

A distributed key-value store implementing consensus and fault tolerance across multiple nodes. Covers the core tradeoffs in distributed systems design — consistency, availability, and partition tolerance.

---

## Skills

**Languages** — C, C++, Rust, SystemVerilog, Python, Java, x86-64 / ARM Assembly  
**Systems** — Operating systems, computer architecture, concurrent programming, compilers  
**Tools** — GDB, QEMU, Valgrind, perf, Git, Make

---

## Coursework

- Computer Architecture
- Operating Systems (Barrelfish on ARM and Unix-like xv6)
- Distributed Systems
- Compilers
- Hardware / Software Interface
- Concurrent Programming
- Discrete structures, linear algebra, and probability

---

## Reading

Things I find worth reading:

- [Userspace threading reading list](https://github.com/shanenelson1117/ReadingLists/blob/main/user_threads_resources.pdf)
- [System interview reading list](https://github.com/shanenelson1117/ReadingLists/blob/main/interview_prep_roadmap.pdf)

