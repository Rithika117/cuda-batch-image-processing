# cuda-batch-image-processing
# CUDA Batch Image Processing

## Overview

This project demonstrates GPU-based batch image processing using CUDA.
The program processes hundreds of images using CUDA kernels for grayscale conversion and edge detection.

The goal of the project is to demonstrate parallel image processing using GPU computation.

## Features

* Batch image processing
* CUDA GPU acceleration
* Grayscale conversion
* Edge detection
* Command line execution
* Parallel processing with CUDA kernels

## Technologies Used

* CUDA C++
* NVIDIA CUDA Toolkit
* GPU Kernels
* CUDA Runtime API

## Folder Structure

```text
src/                 -> CUDA source files
data/input/          -> Input images
data/output/         -> Processed output images
screenshots/         -> Execution proof
```

## Build Instructions

```bash
make
```

## Run Instructions

```bash
./run.sh data/input data/output
```

## Example GPU Operations Used

* cudaMalloc()
* cudaMemcpy()
* CUDA kernels
* Device synchronization

## Results

The application successfully processed a large batch of images using GPU acceleration.

## Learning Outcomes

* CUDA memory management
* GPU kernel execution
* Parallel image processing
* Host-device communication
