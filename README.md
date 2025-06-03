# GPU vs CPU Benchmark

This project benchmarks the training performance of a simple CNN using PyTorch on the CIFAR-10 dataset.

## Phase 1: CPU Benchmark
- Trained on CIFAR-10 using a custom CNN
- Logged training time: **154.25 seconds**
- Accuracy on test set: **53%**
- Per-class performance also measured

## Phase 2: GPU Benchmark (CUDA)

- Trained on CIFAR-10 using custom CNN (same architecture as CPU benchmark).
- Training time: ~111 seconds.
- Test set accuracy: 53% (2 epochs).
- CUDA device fully utilized on Google Colab.
- Full training script and evaluation uploaded.

