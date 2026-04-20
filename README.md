# System-Programming-Project-Description

---

# CSAPP Labs (Computer Systems: A Programmer’s Perspective)

## Disclaimer
In accordance with course policies and academic integrity guidelines, the source code for these labs cannot be publicly disclosed.  
This repository provides a high-level overview of the implementations, focusing on system design, problem-solving approaches, and key technical concepts.

---

## Overview
These projects are part of the CSAPP (Computer Systems: A Programmer’s Perspective) course, designed to build a deep understanding of computer systems from low-level data representation to system-level programming and security.

Each lab focuses on a different abstraction layer of the system, including bit-level operations, assembly analysis, exploitation, process control, and memory management.

---

## Data Lab (Bit-Level Programming)
- Implemented functions using only restricted bitwise operations (e.g., `~`, `&`, `^`, `|`, `+`, `<<`, `>>`)
- No control flow (`if`, `for`, etc.) allowed
- Focused on two’s complement arithmetic and floating-point representation  

**What I learned**
- Internal representation of integers and floating-point numbers  
- Bit-level manipulation and low-level optimization techniques  

---

## Bomb Lab (Reverse Engineering)
- Analyzed a compiled binary with no source code  
- Used tools such as GDB and disassembly to identify correct inputs for each phase  
- Successfully “defused” multiple phases by understanding assembly-level control flow  

**What I learned**
- x86-64 assembly analysis  
- Debugging with GDB  
- Reverse engineering techniques  

---

## Attack Lab (Binary Exploitation)
- Exploited buffer overflow vulnerabilities in provided binaries  
- Performed code injection attacks and Return-Oriented Programming (ROP)  
- Manipulated program control flow at runtime  

**What I learned**
- Stack structure and calling conventions  
- Memory corruption vulnerabilities  
- Practical exploitation techniques  

---

## Shell Lab (Tiny Shell Implementation)
- Implemented a Unix-like command-line shell (`tsh`)  
- Supported job control (foreground/background processes)  
- Handled signals (`SIGINT`, `SIGTSTP`, etc.) and process synchronization  

**What I learned**
- Process management (`fork`, `exec`, `wait`)  
- Signal handling and job control  
- Concurrent process coordination  

---

## Malloc Lab (Dynamic Memory Allocator)
- Built a custom memory allocator similar to `malloc`/`free`  
- Managed heap memory with explicit/implicit free lists  
- Optimized for throughput and memory utilization  

**What I learned**
- Heap layout and memory fragmentation  
- Allocation strategies (first-fit, best-fit, etc.)  
- Low-level memory management and performance trade-offs  

---

## Summary
Through these labs, I gained hands-on experience across multiple layers of computer systems:

- Bit-level data representation  
- Assembly and binary-level analysis  
- Security and exploitation techniques  
- Process and signal handling  
- Memory allocation and performance optimization  

This experience strengthened my ability to reason about system behavior from both a low-level and high-level perspective.
