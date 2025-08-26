# 📘 LLM Infra Learning Roadmap

This roadmap provides a suggested path for learning LLM infrastructure, from foundations to advanced systems design.

## 🟢 Beginner
- **Read**: [Pre-training](pretraining.md) (Overview + Scaling Laws)
- **Key Papers**:
  - [Attention Is All You Need (2017)](https://arxiv.org/abs/1706.03762)
  - [Scaling Laws for Neural Language Models (2020)](https://arxiv.org/abs/2001.08361)
- **Goal**: Understand transformers, pretraining basics, and scaling intuition.

## 🟡 Intermediate
- **Read**: [Post-training & Alignment](posttraining.md), [Inference & Serving](inference.md)
- **Key Papers**:
  - [RLHF (2017)](https://arxiv.org/abs/1706.03741)
  - [InstructGPT (2022)](https://arxiv.org/abs/2203.02155)
  - [vLLM (2023)](https://arxiv.org/abs/2309.06180)
- **Goal**: Learn alignment (SFT, RLHF, DPO) and efficient serving frameworks.

## 🔴 Advanced
- **Read**: [Optimization](optimization.md), [Monitoring & Reliability](monitoring.md)
- **Key Papers & Blogs**:
  - [Chinchilla Scaling (2022)](https://arxiv.org/abs/2203.15556)
  - [Speculative Decoding](https://arxiv.org/abs/2302.01318)
  - [DeepSpeed Fault Tolerance Docs](https://www.deepspeed.ai/tutorials/advanced-fault-tolerance/)
- **Goal**: Master advanced optimizations, observability, and production-scale reliability.