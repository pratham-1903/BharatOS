# BharatOS - Memory Management Day 1

## What is RAM?

RAM is the temporary working memory of a computer.

Programs and data that the CPU needs while the computer is running are stored in RAM.

RAM is much faster than permanent storage such as an SSD or hard disk.

## What is Memory Management?

Memory management is the process of controlling how computer memory is used.

An operating system needs to keep track of which parts of memory are being used and which parts are free.

## What is a Memory Allocator?

A memory allocator is a system that gives a program a portion of available memory when it needs it.

When the memory is no longer needed, the memory can be released and used again.

## Why does an Operating System need Memory Management?

An operating system needs memory management because many programs may need memory at the same time.

The OS must:

- Keep track of used memory.
- Keep track of free memory.
- Give memory to programs.
- Reclaim memory when it is released.
- Prevent programs from incorrectly accessing memory belonging to other programs.

## Future Goal

BharatOS will eventually have its own basic memory management system.
