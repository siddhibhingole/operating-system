# Operating Systems 

This repository contains two C++ programs based on Operating System memory management concepts.

## 1. Memory Allocation Strategies

**Aim:** To implement and compare First Fit, Best Fit, and Worst Fit memory allocation algorithms.

**Memory Blocks (KB):** 100, 500, 200, 300, 600

**Processes (KB):** 212, 417, 112, 426

**Algorithms:**
- First Fit
- Best Fit
- Worst Fit

**Comparison:** Successfully allocated processes, remaining free memory, and memory utilization.

## 2. Page Replacement Algorithms

**Aim:** To implement and compare FIFO, LRU, and Optimal page replacement algorithms.

**Page Reference String:** 7, 0, 1, 2, 0, 3, 0, 4, 2, 3, 0, 3, 2

**Number of Frames:** 3

**Algorithms:**
- FIFO (First In, First Out)
- LRU (Least Recently Used)
- Optimal Page Replacement

**Comparison:** Frame contents after each page reference, total page faults, and page hits.

## Technologies Used
- Programming Language: C++
- Concepts: Operating Systems, Memory Management, Page Replacement

## How to Run

Compile and run each program using a C++ compiler:

```bash
g++ filename.cpp -o program
./program
```

On Windows, run the compiled program using:

```bash
program.exe
```

## Conclusion

These programs demonstrate memory allocation and page replacement techniques and compare their performance using the same input values.
