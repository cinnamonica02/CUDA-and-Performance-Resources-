# GPU Engineer Toolkit 🚀

This repository contains a curated list of resources, tools, and examples organized by category to help GPU engineers maximize performance and efficiency.

---

## Quick Links 🔗

| Category | Description |
|---|---|
| [CUDA Basics](#cuda-basics) 🤓 | Fundamental CUDA concepts and resources |
| [cuBLAS & Linear Algebra](#cublas--linear-algebra) 🧮 | Resources for linear algebra on CUDA |
| [Kernel Optimization](#kernel-optimization) ✨ | Techniques for optimizing CUDA kernels |
| [Flash Attention](#flash-attention) ⚡ | Resources related to Flash Attention |
| [CUTLASS](#cutlass) 🔪 | NVIDIA's CUTLASS library resources |
| [Debugging & Profiling](#debugging--profiling) 🐞 | Tools for debugging CUDA code |
| [Distributed Learning](#distributed-learning) 🌐 | Resources on distributed training |
| [Interesting Repos](#interesting-repos) 💡 | Curated GitHub repositories |
| [Extra Optimization](#extra-optimization) ➕ | General optimization resources |

---

## CUDA Basics 🤓

Fundamental CUDA concepts and learning resources.

| Resource | Description | Link |
|---|---|---|
| Simon Boehm's cuBLAS Article | In-depth and intuitive explanation of cuBLAS. | [Link](https://siboehm.com/articles/22/CUDA-MMM) |
| Elliot Arledge CUDA Course | Full 12-hour CUDA course on YouTube. | [Link](https://www.youtube.com/watch?v=86FAWCzIe_4&t=17124s) |
| PMPP 3rd Edition | Parallel Programming: Principles and Practice - Good resource (local file). | (Download pdf in your local machine) |
| NVIDIA CUDA Documentation | Official CUDA documentation. | [Link](https://docs.nvidia.com/cuda/) |
| Nick - Coffee Before Arch | Interesting and Goated Github Profile | [Link](https://github.com/coffeebeforearch) |

---

## cuBLAS & Linear Algebra 🧮

Resources and examples for leveraging cuBLAS for linear algebra operations.

| Resource | Description | Link |
|---|---|---|
| Simon Boehm's cuBLAS Article | In-depth and intuitive explanation of cuBLAS. | [Link](https://siboehm.com/articles/22/CUDA-MMM) |
| DeepGEMM | High-performance GEMM kernels from Deepseek AI. | [Link](https://github.com/deepseek-ai/DeepGEMM) |

---

## Kernel Optimization ✨

Tools and techniques for optimizing CUDA kernel performance.

| Resource | Description | Link |
|---|---|---|
| Kernel Fusion Lecture by Kapil Sharma | Explanation of kernel fusion in GPU mode. | [Link](https://www.youtube.com/watch?v=m6BSREnQ84U&t=88s) |
| Softmax Kernel + Visualization | Writing a softmax kernel with visualization (Simon Oz). | [Link](https://www.youtube.com/watch?v=IpHjDoW4ffw) |
| Colfax Blogs | Collection of optimization-related blog posts from Colfax. | [Link](https://research.colfax-intl.com/research/) |

---

## Flash Attention ⚡

Resources related to Flash Attention.

| Resource | Description | Link |
|---|---|---|
| Flash Attention Repository | Official repository for Flash Attention. | [Link](https://github.com/Dao-AILab/flash-attention) |
| Jay Shah CUTLASS + Flash Attention Talk | GPU mode talk on CUTLASS and Flash Attention 3. | [Link](https://www.youtube.com/watch?v=JwUcZwPOCpA&t=703s) |
| Flash Attention Viz (Manim) | Visualization of Flash Attention using Manim. | [Link](https://www.youtube.com/watch?v=-EF-KIscwJw) |
| FlashMLA | Flash-accelerated machine learning algorithms from Deepseek AI. | [Link](https://github.com/deepseek-ai/FlashMLA) |

---

## CUTLASS 🔪

Resources for NVIDIA's CUTLASS library.

| Resource | Description | Link |
|---|---|---|
| Colfax CUTLASS Articles | Various tutorials on CUTLASS features. | [Link](https://research.colfax-intl.com/category/cutlass/) |
| CUTLASS Docker Container | Instructions for setting up a CUTLASS development environment in Docker. | [Link](https://leimao.github.io/blog/Build-Develop-CUTLASS-CUDA-Kernels/) |
| CUTLASS Video Lectures | Various video lectures on CUTLASS. | [Link](https://www.youtube.com/playlist?list=PL8fVUTBmJhHJsvQekHA5V99F-j80oO6Yj) |

---

## Debugging & Profiling 🐞

Tools for debugging CUDA code.

| Resource | Description | Link |
|---|---|---|
| NVIDIA Nsight Systems | NVIDIA's performance analysis tool. | [Link](https://developer.nvidia.com/nsight-systems) |
| CUDA-GDB | Debugging tool for GPU code. | [Link](https://developer.nvidia.com/cuda-gdb) |

---

## Distributed Learning 🌐

Resources on distributed training.

| Resource | Description | Link |
|---|---|---|
| Hugging Face Ultra-Scale Playbook | Training LLMs on GPU clusters. | [Link](https://huggingface.co/papers/2311.10799) |
| Ferdinand Mom's Videos | Videos on distributed learning (YouTube channel). | [Link](https://www.youtube.com/@FerdinandMom/videos) |

---

## Interesting Repos 💡

Curated GitHub repositories.

| Resource | Description | Link |
|---|---|---|
| Lauralie Wired - Deepseek Reverse Engineering | Reverse engineering Deepseek open-source repo PTX. | [Link](https://github.com/LaurieWired/BenchmarkCustomPTX) |
| CUDA Ray Tracer | CUDA implementation of a ray tracer. | [Link](https://github.com/rajneel18/100_CUDA_Kernels/blob/main/Day44/cuda_ray_tracer.cu) |
| pyspur.dev Blog | Further analysis into Deepseek Open Source week and reverse engineering | [Link](https://www.pyspur.dev/blog/deepseek_open_source_week) |
| Ly33n (100 Days of GPU) | Goated GPU kernel implementations. | [Link](https://github.com/1y33/100Days/) |
| Hamdi (100 Days of GPU) | More GPU kernel implementations. | [Link](https://github.com/a-hamdi/GPU) |
| Insightful Kernels | GitHub repos with insightful CUDA kernels. | [Link](https://github.com/NVIDIA/cuda-samples) |

---

## Extra Optimization ➕

General optimization resources (not limited to CUDA).

| Resource | Description | Link |
|---|---|---|
| Triton Resources | Resources for Triton. | [Link](https://triton-lang.org/) |
| Unsloth Optimization Tasks | Triton intergration to optimize | [Link](https://colab.research.google.com/drive/17kWwpBkGGrBCbn74NP6rEOTy21KwJ8pR?authuser=1) |

---

## Getting Started

Instructions on how to use this repository.

### Prerequisites


### Ideal Set-up : Running locally

*   NVIDIA GPU with CUDA support
*   CUDA Toolkit installed
*   (Optional) Docker for CUTLASS development


### No GPU ? Dont let that discourage you! 

* You can run cuda kernels on google colab
* There are also more affordable GPU cloud instances like runpod.io, lambda labs , vast.ai etc
* Currently the discord channel of Umar Jamil is running a 100 days of cuda ,
- you may be able to get sponsors if you cook everyday there, 
- everything is possible when you build consistently in public!

### Installation/Setup

