# GPU vs CPU Benchmark

This project benchmarks the training performance of a simple CNN using PyTorch on the CIFAR-10 dataset.

## Phase 1: CPU Benchmark
- Trained on CIFAR-10 using a custom CNN
- Logged training time: **154.25 seconds**
- Accuracy on test set: **53%**
- Per-class performance also measured

## Upcoming Phases
- Porting to GPU with CUDA
- Measuring speedup and profiling memory
- Quantization and TensorRT optimization
