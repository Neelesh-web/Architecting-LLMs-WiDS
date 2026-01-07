# 🧠 Architecting LLMs: Building a GPT from Scratch

This repository documents my progress through a **6-week mentorship track** focused on building a **GPT-style language model from first principles**, inspired by Andrej Karpathy’s *Zero-to-Hero* approach.

The objective is not just to *use* large language models, but to **understand and implement the core machinery that makes them work**.

---

## ✅ Progress Overview

- ✔ **Week 1 completed** — Autograd & Backpropagation from scratch  
- ✔ **Week 2 completed** — Bigram Language Models & Tensor Foundations  
- ⏳ Upcoming — MLPs, BatchNorm, WaveNets, Transformers, GPT

---

## 📅 Week 1 — The Engine of AI: Autograd & Backpropagation

**Focus:** Understanding gradients, the chain rule, and automatic differentiation by implementing everything manually.

### What I Implemented

- Built a scalar-based **automatic differentiation engine** (`Value` object)
- Constructed a **computation graph** with forward & backward passes
- Implemented **manual backpropagation** using the chain rule
- Supported core operations:
  - Addition, multiplication
  - Power, division, negation
  - `exp()` and `log()`
- Implemented **topological sorting** for correct gradient flow
- Verified gradients numerically and analytically
- Implemented **Softmax + Negative Log Likelihood (NLL) loss**
- Cross-verified gradients using **PyTorch autograd**

### Key Concepts Mastered

- Analytical vs numerical derivatives
- Finite difference & symmetric derivative approximations
- Gradient accumulation
- Why backpropagation works (not just how)

📂 **Relevant files**



---

## 📅 Week 2 — Language Modeling Foundations: Bigrams & Tensors

**Focus:** Understanding how language models work at the most fundamental level.

### What I Implemented

- Built a **character-level Bigram Language Model**
- Implemented tokenization and count-based probability estimation
- Trained the model using **Negative Log Likelihood loss**
- Sampled text from learned probability distributions
- Transitioned from pure Python to **PyTorch tensors**
- Practiced tensor operations:
  - Indexing
  - Broadcasting
  - Shape reasoning

### Key Concepts Mastered

- What “language modeling” actually means
- How logits are converted into probabilities (softmax)
- Sampling vs greedy decoding
- Why tensors are central to deep learning

📂 **Relevant files**
