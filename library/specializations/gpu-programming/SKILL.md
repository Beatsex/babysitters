---
name: specialization-gpu-programming
description: "GPU Programming and Parallel Computing is a specialized domain focused on leveraging the massive parallelism of Graphics Processing Units (GPUs) to solve computationally intensive problems. Modern GPUs contain thousands of cores designed for executing thousands of threads simultaneously, making…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: gpu-programming
  process-count: 25
---

# specialization-gpu-programming

## Overview

GPU Programming and Parallel Computing is a specialized domain focused on leveraging the massive parallelism of Graphics Processing Units (GPUs) to solve computationally intensive problems. Modern GPUs contain thousands of cores designed for executing thousands of threads simultaneously, making them ideal for data-parallel workloads that would be prohibitively slow on traditional CPUs.

## Available Processes (25)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/gpu-programming/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `atomic-operations-synchronization` (`specializations/gpu-programming/atomic-operations-synchronization`) | Atomic Operations and Synchronization Patterns - Process for correctly and efficiently using |
| `compute-shader-development` (`specializations/gpu-programming/compute-shader-development`) | Compute Shader Development - Process for developing compute shaders using graphics APIs |
| `cuda-kernel-development` (`specializations/gpu-programming/cuda-kernel-development`) | CUDA Kernel Development Workflow - End-to-end process for developing, testing, and deploying CUDA kernels. |
| `cuda-stream-concurrency` (`specializations/gpu-programming/cuda-stream-concurrency`) | CUDA Stream and Concurrency Management - Process for implementing concurrent kernel execution |
| `custom-cuda-operator-development` (`specializations/gpu-programming/custom-cuda-operator-development`) | Custom CUDA Operator Development for Deep Learning - Process for developing custom CUDA kernels |
| `dynamic-parallelism-implementation` (`specializations/gpu-programming/dynamic-parallelism-implementation`) | Dynamic Parallelism Implementation - Process for utilizing CUDA dynamic parallelism to launch |
| `gpu-cluster-computing` (`specializations/gpu-programming/gpu-cluster-computing`) | GPU Cluster Computing - Process for scaling GPU workloads across distributed clusters |
| `gpu-cpu-data-transfer-optimization` (`specializations/gpu-programming/gpu-cpu-data-transfer-optimization`) | GPU-CPU Data Transfer Optimization - Workflow for minimizing data transfer overhead between |
| `gpu-debugging-techniques` (`specializations/gpu-programming/gpu-debugging-techniques`) | GPU Debugging Techniques - Systematic approach to debugging GPU code, identifying race conditions, |
| `gpu-image-video-processing` (`specializations/gpu-programming/gpu-image-video-processing`) | GPU-Accelerated Image and Video Processing - Workflow for implementing GPU-accelerated |
| `gpu-memory-optimization` (`specializations/gpu-programming/gpu-memory-optimization`) | GPU Memory Optimization - Systematic approach to optimizing GPU memory access patterns, |
| `gpu-memory-pool-allocator` (`specializations/gpu-programming/gpu-memory-pool-allocator`) | GPU Memory Pool and Allocator Design - Workflow for implementing custom GPU memory allocators |
| `gpu-performance-regression-testing` (`specializations/gpu-programming/gpu-performance-regression-testing`) | GPU Performance Regression Testing - Workflow for establishing and maintaining GPU performance |
| `hip-porting-cross-platform` (`specializations/gpu-programming/hip-porting-cross-platform`) | HIP Porting and Cross-Platform Development - Workflow for porting CUDA applications to AMD GPUs |
| `ml-inference-optimization` (`specializations/gpu-programming/ml-inference-optimization`) | Machine Learning Inference Optimization - Workflow for optimizing GPU-accelerated ML model |
| `multi-gpu-programming` (`specializations/gpu-programming/multi-gpu-programming`) | Multi-GPU Programming - Process for scaling applications across multiple GPUs within a single node |
| `occupancy-optimization` (`specializations/gpu-programming/occupancy-optimization`) | Occupancy Optimization - Process for optimizing SM occupancy by balancing resource usage |
| `opencl-application-development` (`specializations/gpu-programming/opencl-application-development`) | OpenCL Application Development - Process for developing portable GPU applications using OpenCL. |
| `parallel-algorithm-design` (`specializations/gpu-programming/parallel-algorithm-design`) | Parallel Algorithm Design - Process for designing efficient parallel algorithms that exploit GPU architecture. |
| `performance-profiling-analysis` (`specializations/gpu-programming/performance-profiling-analysis`) | Performance Profiling and Analysis - Comprehensive workflow for profiling GPU applications, |
| `reduction-scan-implementation` (`specializations/gpu-programming/reduction-scan-implementation`) | Reduction and Scan Algorithm Implementation - Workflow for implementing efficient parallel |
| `shared-memory-usage-patterns` (`specializations/gpu-programming/shared-memory-usage-patterns`) | Shared Memory Usage Patterns - Process for effectively utilizing shared memory for inter-thread |
| `stencil-computation-optimization` (`specializations/gpu-programming/stencil-computation-optimization`) | Stencil Computation Optimization - Process for optimizing stencil computations (neighbor-based operations) |
| `tensor-core-programming` (`specializations/gpu-programming/tensor-core-programming`) | Tensor Core Programming - Workflow for utilizing NVIDIA Tensor Cores for accelerated |
| `warp-efficiency-optimization` (`specializations/gpu-programming/warp-efficiency-optimization`) | Warp/Wavefront Efficiency Optimization - Workflow for minimizing warp divergence and maximizing |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `gpu-programming` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
