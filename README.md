# Awesome HPC

A collection of interesting HPC Resources. Not really including papers--there's lots of good info in blog posts and inside documentation, but it's impossible to remember all of the different links. I think it's necessary to maintain a list like this.

## Conferences

- [PPoPP 2025](https://ppopp25.sigplan.org/program/program-PPoPP-2025/)
- [MLSys 2024](https://proceedings.mlsys.org/paper_files/paper/2024)
- [MLSys 2023](https://mlsys.org/virtual/2023/papers.html?filter=titles)
- [ICPP 2024](https://icpp2024.org/index.php?option=com_content&view=article&id=6&Itemid=114)

## Matrix Multiplication and Linear Algebra

References and tools regarding efficient implementation of GEMM and other BLAS-style kernels
on CPUs and GPUs

- [CUTLASS](https://github.com/NVIDIA/cutlass/tree/main) has good info on fast GEMM.
- [BLIS](https://github.com/flame/blis)
- [Reverse Engineering cuBLAS](https://fabianschuetze.github.io/category/articles.html)
- [DeepSeek DeepGEMM](https://github.com/deepseek-ai/DeepGEMM)

## ML Performance

### Frameworks

- [PyTorch 2](https://pytorch.org/assets/pytorch2-2.pdf)
- [ASPLOS Pytorch 2](https://github.com/pytorch/workshops/blob/master/ASPLOS_2024/README.md)
- [ThunderKittens](https://github.com/HazyResearch/ThunderKittens/tree/e5cb89f29e1abb9498ebf8bc878015f9699ee846)
- [triton](https://github.com/triton-lang/triton)

### Efficient Implementations

#### Flash Attention

The premise of FlashAttention is fairly simple. This includes the main
papers and some references for the "backbone" ideas. I.e., IO complexity,
softmax normalization, etc.

- [Data movement is all you need](https://arxiv.org/abs/2007.00072)
- [The Hardware Lottery](https://arxiv.org/abs/2009.06489)
- [IO Complexity of sorting and related problems](https://dl.acm.org/doi/10.1145/48529.48535)
- [Online Softmax Normalizer](https://arxiv.org/abs/1805.02867)
- [Self-attention does not need $O(n^2)$ memory](https://arxiv.org/abs/2112.05682)
- [FlashAttention 1](https://arxiv.org/abs/2205.14135)
- [FlashAttention 2](https://arxiv.org/abs/2307.08691)
- [FlashAttention 3, for H100. Uses Asynchrony and low precision](https://arxiv.org/abs/2407.08608)

## NVIDIA

### Architecture

### Cuda

### PTX

[PTX Docs](https://docs.nvidia.com/cuda/parallel-thread-execution/)