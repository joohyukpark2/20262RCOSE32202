# 20262RCOSE32202

## About This Repository

This repository is created for the Operating Systems Lab course.

It contains documentation and learning notes related to operating systems.

## Topics

- Linux Kernel
- System Calls
- Process Management

## Linux Kernel

The Linux kernel is the core component of the operating system.

It manages system resources such as CPU, memory, and processes.

In this course, I learned how user programs interact with the Linux kernel through system calls.

## System Calls

A system call provides an interface between user applications and the operating system kernel.

User programs use system calls to request services such as file operations, process creation, and memory management.

In this course, I practiced implementing custom system calls in the Linux kernel.

## Process Management

Process management is an important responsibility of an operating system.

The operating system creates, schedules, and terminates processes while managing system resources.

In Linux, the fork() system call creates a new process, while exec() replaces the current process image with a new program.

I learned how process creation and execution work in Linux.

## CPU Scheduling

CPU scheduling determines which process should use the CPU at a given time.

Different scheduling algorithms are used to improve system performance and responsiveness.

Some common scheduling algorithms include:

- First-Come, First-Served (FCFS)
- Shortest Job First (SJF)
- Shortest Remaining Time First (SRTF)
- Round Robin (RR)

I studied how these algorithms affect waiting time, turnaround time, and CPU utilization.

## Memory Management

Memory management is a fundamental function of an operating system.

The operating system allocates and manages memory resources for running processes.

Important concepts in memory management include:

- Virtual Memory
- Paging
- Memory Allocation
- Address Translation
- Stack and Heap Memory

Virtual memory allows processes to use their own virtual address spaces, while paging helps manage memory efficiently.

I studied how operating systems manage memory and provide memory protection between processes.

## Inter-Process Communication (IPC)

Inter-Process Communication (IPC) allows processes to exchange data and coordinate their activities.

Common IPC mechanisms include:

- Pipes
- Message Queues
- Shared Memory
- Sockets
- Signals

Pipes provide a simple way to transfer data between processes, while shared memory allows multiple processes to access a common memory region.

I learned how different IPC mechanisms support communication between processes in Linux.

