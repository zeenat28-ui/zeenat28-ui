# Zeenat Riaz

**ML Systems & Inference Engineer | Security & Forensics Specialist**

[LinkedIn](https://www.linkedin.com/in/zeenat-riaz-16339b3ab/) • [Email](mailto:your.email@example.com) • Pakistan

---

## OVERVIEW

I am an ML Systems Engineer focused on inference optimization, hardware acceleration, and secure infrastructure. My work revolves around resolving deep-level bottlenecks for AI frameworks on both GPU and NPU architectures, streamlining containerized deployments, and hardening model-serving pipelines against supply-chain vulnerabilities. 

With a background in Digital Forensics and Full-Stack Development, I build systems that are performant at the hardware level and mathematically sound, while ensuring strict isolation and security from the backend to the UI.

## ENGINEERING FOCUS & EVIDENCE

### ML Compute & Hardware Acceleration
* **ROCm/HIP on GPUs:** Optimized AMD ROCm Docker infrastructure by decoupling HIP compiler toolchains from prebuilt math libraries. This resolved distribution-aware package resolution and reduced the container footprint by **>90% (from 7.94 GB to 745 MB)** (PR #8360).
* **Inference Engine Optimization:** Diagnosed and resolved complex indexer geometry scaling and memory cache block allocation for DeepSeek-V4.1-Flash execution on NVIDIA SM120 (Blackwell) architectures within **vLLM** (PR #56509).
* **XDNA NPU via ONNX Runtime:** Hardened edge NPU inference pipelines for the **AMD Ryzen AI** project. Engineered an isolated Docker quantization pipeline for INT8 Post-Training Quantization (PTQ), successfully resolving ABI dependency conflicts and preventing driver corruption (PR #403).

### Secure Infrastructure & Full-Stack Platforms
* **Model Artifact & Supply-Chain Security:** Architected **SanityX**, a zero-trust Content Disarm and Reconstruction (CDR) platform that intercepts and sanitizes complex file structures (PDF, DOCX, ZIP) at the binary level to strip embedded polymorphic threats.
* **Full-Stack Chain of Custody:** Engineered **ForensicVideo-X** using Go, .NET, and React.js. The platform integrates deepfake detection heuristics with immutable digital chain-of-custody logging.
* **Session Integrity Engine:** Built **SHIELD OS**, a session integrity system utilizing a Go background agent and a Python FastAPI risk engine to dynamically bind active user sessions to cryptographic software machine fingerprints.

## TECHNOLOGIES

**ML Infrastructure & Hardware Frameworks**
<br>
<img src="https://skillicons.dev/icons?i=pytorch,docker,linux&theme=dark" />
<br>
*ONNX Runtime, vLLM, AMD ROCm/HIP, Ryzen AI (XDNA), NVIDIA CUDA*

**Systems & Backend**
<br>
<img src="https://skillicons.dev/icons?i=cpp,go,py,c,bash&theme=dark" />

**Security & UI**
<br>
<img src="https://skillicons.dev/icons?i=react,tailwind,figma&theme=dark" />
<br>
*Volatility, KAPE, Autopsy, Wireshark, Zero-Trust Architecture*

---
