# Awesome LLM Infra [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources on **Large Language Model (LLM) infrastructure** — from **pre-training** and **post-training** to **inference** and **serving at scale**.  
> Covering system design, distributed training, optimization techniques, and cutting-edge research.

💡 Looking for in-depth explanations and diagrams? Check out the [Guidebook](guidebook/README.md) for a mini-handbook style version of this repo.

📘 Want a structured path? Explore the [Learning Roadmap](guidebook/roadmap.md) for step-by-step guidance.

---

## 📚 Contents

- [Pre-training](#-pre-training)
- [Post-training & Alignment](#-post-training--alignment)
- [Inference & Serving](#-inference--serving)
- [Optimization](#-optimization)
- [Monitoring & Reliability](#-monitoring--reliability)
- [References](#-references)
  - [Papers](#papers)
  - [Blogs & Engineering Posts](#blogs--engineering-posts)
  - [Talks & Courses](#talks--courses)
- [Contributing](#-contributing)

---

## 🔥 Pre-training
- [Scaling Laws for Neural Language Models](https://arxiv.org/abs/2001.08361) – Kaplan et al., 2020  
- [PaLM: Scaling Language Models](https://arxiv.org/abs/2204.02311) – Chowdhery et al., 2022  
- [Megatron-LM](https://github.com/NVIDIA/Megatron-LM) – Training trillion-parameter models.  
- [DeepSpeed](https://github.com/microsoft/DeepSpeed) – Distributed training and ZeRO optimizations.  

---

## 🎯 Post-training & Alignment
- [Fine-Tuning Language Models from Human Preferences (RLHF)](https://arxiv.org/abs/1706.03741) – Christiano et al., 2017  
- [Direct Preference Optimization (DPO)](https://arxiv.org/abs/2305.18290) – Rafailov et al., 2023  
- [Constitutional AI](https://arxiv.org/abs/2212.08073) – Anthropic’s alignment method.  
- [LoRA: Low-Rank Adaptation](https://arxiv.org/abs/2106.09685) – Efficient fine-tuning.  

---

## ⚡ Inference & Serving
- [vLLM](https://github.com/vllm-project/vllm) – High-throughput inference engine.  
- [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) – NVIDIA’s optimized inference stack.  
- [Triton Inference Server](https://github.com/triton-inference-server/server) – Production-scale serving.  
- [Petals](https://github.com/bigscience-workshop/petals) – Collaborative inference of large models.  

---

## 🛠 Optimization
- [Quantization](https://arxiv.org/abs/2210.17323) – 8-bit, 4-bit quantization methods (GPTQ, AWQ).  
- [Knowledge Distillation](https://arxiv.org/abs/1503.02531) – Compressing large models into smaller ones.  
- [Mixture-of-Experts (MoE)](https://arxiv.org/abs/1701.06538) – Efficient scaling with sparse activation.  

---

## 🕵️ Monitoring & Reliability
- [Prometheus + Grafana](https://prometheus.io/) – Monitoring LLM system health.  
- [LLM Observability Guide (Weights & Biases)](https://wandb.ai/site/articles/observability-for-llms) – Logging, tracing, debugging.  
- Fault tolerance in distributed training – [DeepSpeed Fault Tolerance](https://deepspeed.readthedocs.io/en/latest/fault_tolerance.html).  

---

## 📖 References

### Papers
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) – Vaswani et al., 2017  
- [Chinchilla: Training Compute-Optimal Models](https://arxiv.org/abs/2203.15556) – Hoffmann et al., 2022  
- [Sparks of AGI](https://arxiv.org/abs/2303.12712) – Microsoft Research, 2023  

### Blogs & Engineering Posts
- [OpenAI Engineering Blog](https://openai.com/research)  
- [Anthropic Research Blog](https://www.anthropic.com/index/research)  
- [Meta AI Blog](https://ai.meta.com/research/publications/)  
- [DeepSpeed Blog](https://www.deepspeed.ai/)  

### Talks & Courses
- [Stanford CS324: Large Language Models](https://web.stanford.edu/class/cs324/)  
- [Hugging Face Course](https://huggingface.co/course/chapter1)  
- [Efficient LLM Training & Inference (AWS)](https://www.youtube.com/watch?v=l2Wc2kFGYfU)  

---

## 🤝 Contributing
Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a PR.  
Feel free to add new references, tools, or write summaries.

---

## ⭐ License
[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a  
[Creative Commons Attribution 4.0 International License][cc-by].

[cc-by]: http://creativecommons.org/licenses/by/4.0/  
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg