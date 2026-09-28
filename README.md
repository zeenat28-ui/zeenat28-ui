# Zeenat Riaz

**Systems & MLOps Engineer | Distributed ML Infrastructure & Hardware Acceleration**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Zeenat%20Riaz-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/zeenat-riaz-16339b3ab/)
[![Email](https://img.shields.io/badge/Email-zeenatriaz468%40gmail.com-EA4335?style=flat&logo=gmail)](mailto:zeenatriaz468@gmail.com)
[![GitHub PRs](https://img.shields.io/badge/Open%20Source-Contributions-181717?style=flat&logo=github)](https://github.com/pulls?q=is%3Apr+author%3Azeenat28-ui+-user%3Azeenat28-ui)

I engineer resilient distributed training pipelines, high-throughput LLM inference architectures, and hardware-accelerated systems spanning NVIDIA CUDA, AMD ROCm, and NPU runtimes.

---

### 🏆 Featured Distributed ML & Open-Source Infrastructure Contributions

| Project | PR / Issue | Scope & Technical Impact | Review Status |
| :--- | :--- | :--- | :--- |
| **🤗 Hugging Face Accelerate** | [**PR #4346**](https://github.com/huggingface/accelerate/pull/4346) <br> *(Fixes [#4330](https://github.com/huggingface/accelerate/issues/4330))* | **Distributed Checkpoint Resumption & Shuffle Permutation Sync** <br> Fixed a silent data corruption bug where mid-epoch resumption via `skip_first_batches` left source `DataLoaderShard` / `DataLoaderDispatcher` iterations desynchronized, causing subsequent epochs to repeat previous shuffle permutations. Implemented bidirectional iteration propagation, nested batch sampler epoch delegation in `SkipBatchSampler`, and decoupled `SeedableRandomSampler` persistence. | `Approved` |
| **🤗 Hugging Face Accelerate** | [**PR #4345**](https://github.com/huggingface/accelerate/pull/4345) | **Megatron-LM Distributed Barrier Synchronization** <br> Resolved race conditions where non-main worker ranks bypassed synchronization in `PartialState.wait_for_everyone()`, ensuring deterministic distributed barrier execution across Megatron-LM tensor/pipeline parallel ranks. | `Approved` |
| **🤗 Hugging Face Hub** | [**PR #5017**](https://github.com/huggingface/huggingface_hub/pull/5017) | **Card Front Matter Scalar Tag Normalization** <br> Prevented silent metadata degradation in YAML parser where single scalar tags in repository cards were split into character-level arrays during automated model indexing. | `Approved` |
| **⚡ vLLM** | [**vllm-project/vllm**](https://github.com/vllm-project/vllm) | **High-Throughput LLM Inference & Serving** <br> Memory-efficient KV cache paging, tensor parallelism, and low-latency continuous batching across heterogeneous accelerators. | `Active Fork` |
| **🔴 AMD ROCm** | [**ROCm/TheRock**](https://github.com/ROCm/TheRock) | **HIP & ROCm Build Systems** <br> Cross-vendor hardware abstraction, unified GPU kernels, and runtime compilation toolchains for AMD accelerators. | `Active Fork` |

---

### 🛠️ Core Systems Architecture & Featured Projects

- [**Project Nexus**](https://github.com/zeenat28-ui/project-nexus) — Distributed ML integration fabric bridging NVIDIA CUDA and AMD ROCm under a hybrid C++/Python architecture with custom VRAM memory pooling and collective communication fabrics.
- [**ROS 2 Edge Perception**](https://github.com/zeenat28-ui/ros2-edge-perception) — Enterprise-grade 3D edge perception & AMR autonomy stack (ISO 3691-4 & VDA 5050 compliant) with real-time tensor inference.
- [**AuditPulse Core**](https://github.com/zeenat28-ui/auditpulse-core) — High-performance AST static security analyzer and CLI engine for smart contract vulnerability detection.

---

### 💻 Technical Toolchain

- **Distributed ML & Training:** PyTorch, Accelerate, DeepSpeed, Megatron-LM, FSDP, Horovod
- **Inference Engines & Runtimes:** vLLM, ONNX Runtime, TensorRT, ROCm / HIP, Ryzen AI (XDNA)
- **Systems & Languages:** Python, Modern C++ (17/20), Go, CUDA, Bash
- **MLOps & Infrastructure:** Docker, Kubernetes, Linux Internals, SLURM, CI/CD Actions
