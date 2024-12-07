# Introduction

本节主要介绍LLaMA的基本架构和流程。

LLaMA1、LLaMA2、LLaMA3在架构上几乎没有变化。

- [LLaMA1](https://arxiv.org/abs/2302.13971)：**Pre-normalization+RMSNorm、SwiGLU、RoPE**
- [LLaMA2](https://arxiv.org/abs/2307.09288)：**GQA**、longer context length
- [LLaMA3](https://arxiv.org/abs/2407.21783)：同一序列不同Doc用AttentionMask区分、tiktoken+更大的词表（128k）、RoPE参数到500000

