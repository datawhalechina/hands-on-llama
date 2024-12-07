# Introduction

## Base

本节主要介绍LLaMA的基本架构和流程。

LLaMA1、LLaMA2、LLaMA3在架构上几乎没有变化。

- [LLaMA1](https://arxiv.org/abs/2302.13971)：**Pre-normalization+RMSNorm、SwiGLU、RoPE**
- [LLaMA2](https://arxiv.org/abs/2307.09288)：**GQA**、longer context length
- [LLaMA3](https://arxiv.org/abs/2407.21783)：同一序列不同Doc用AttentionMask区分、tiktoken+更大的词表（128k）、RoPE参数到500000

## Task

1. 执行Notebook代码，并尝试修改其中参数，观察运行结果。
2. 尝试了解以下问题：
    1. Attention的本质是什么？
    2. Attention计算时如果不进行缩放可能会发生什么？
    3. FFN为什么要先宽后窄？
    4. LLM为什么要设计多层？
    5. PreNormalization的目的是什么？
3. 理解解码时Position的作用。
4. 理解模型和Tokenizer的转换。
