# ImpossibleCS

We build a unified computing platform that combines software, hardware, and intelligent execution across CPUs, GPUs, NPUs, and custom accelerators.

## Three Projects. One Computing Platform.

### [Impossible-CUDA](https://github.com/ImpossibleCS/impossible-cuda)

**Project 1 · CUDA-to-NPU Compiler SDK**

Impossible-CUDA gives existing CUDA software a new path to execution by translating and compiling CUDA workloads through a modular intermediate representation.

It is designed to run CUDA syntax across a range of NPU backends with near-native performance, reducing dependence on expensive and power-intensive GPU infrastructure.

**Core value:** CUDA compatibility · modular compiler IR · portable NPU execution · near-native performance

---

### [Impossible-Accelerator](https://github.com/ImpossibleCS/impossible-accelerator)

**Project 2 · Physical Low-Cost NPU**

Impossible-Accelerator transforms Impossible-CUDA from a software SDK into a complete hardware platform.

It is a physical NPU designed specifically for CUDA workloads, with the goal of delivering strong acceleration at lower power consumption and lower cost than traditional GPUs such as NVIDIA hardware.

**Core value:** dedicated NPU hardware · low power · low cost · direct CUDA execution

---

### [Impossible-Compiler](https://github.com/ImpossibleCS/impossible-compiler)

**Project 3 · Universal CPU and GPU Compiler**

Impossible-Compiler removes the need to learn GPU-specific programming languages.

It will compile standard C, C++, and Rust directly to CPUs or GPUs, using an intelligent analyzer to determine where each part of a program should run.

**Core value:** unified programming model · automatic CPU/GPU placement · no CUDA or shader rewrite · future-proof execution

---

## The Complete Platform

Together, the three projects create a vertically integrated computing ecosystem:

- **Impossible-Compiler** determines how standard software should run.
- **Impossible-CUDA** provides CUDA compatibility and portable compiler infrastructure.
- **Impossible-Accelerator** supplies purpose-built physical hardware.
- **The unified result** is software that can run efficiently across CPUs, GPUs, and low-cost NPUs without specialized GPU programming.

## Our Vision

To make high-performance computing easier to access, easier to program, and less dependent on expensive, high-power hardware—building a platform that could connect standard software, CUDA applications, intelligent compilers, and custom physical accelerators.
