# AI Engineering Roadmap

> **Mission**
>
> Master Artificial Intelligence from first principles by understanding, implementing, experimenting with, and deploying modern AI systems.
>
> This roadmap is designed around **deep understanding**, not superficial coverage. Every topic is categorized based on its importance to becoming an AI Engineer specializing in Large Language Models (LLMs), Agentic AI, and Production AI.

---

# Mastery Levels

| Level | Description |
|--------|-------------|
| 🟢 Core | Must master. Able to explain, implement, experiment with, optimize, and teach the concept. |
| 🟡 Supporting | Understand well. Know how it works and when to use it. |
| ⚪ Awareness | Know what it is, why it exists, and where it fits in the AI ecosystem. |

---

# Phase 0 — Learning Foundations

> Become an engineer before becoming an AI engineer.

## 🟢 Core

- Git & GitHub
- Python for AI
- Virtual Environments
- Package Management
- NumPy
- Matplotlib
- Debugging
- Project Structure
- Clean Code
- Reading Research Papers
- Experiment Tracking

## 🟡 Supporting

- Object-Oriented Programming
- Pandas
- Jupyter Notebooks
- Docker

---

# Phase 1 — Mathematics for AI

> Understand the mathematics behind AI rather than memorizing formulas.

## 🟢 Core

- Scalars
- Vectors
- Matrices
- Matrix Shapes
- Matrix Multiplication
- Dot Product
- Matrix Transpose
- Derivatives
- Chain Rule
- Gradients
- Probability
- Probability Distributions
- Mean
- Variance

## 🟡 Supporting

- Eigenvalues
- Eigenvectors
- Singular Value Decomposition (SVD)

---

# Phase 2 — Machine Learning

> Learn why machines can learn from data.

## 🟢 Core

- What is Machine Learning?
- Datasets
- Features & Labels
- Training / Validation / Test Sets
- Supervised Learning
- Loss Functions
- Optimization
- Gradient Descent
- Stochastic Gradient Descent (SGD)
- Adam Optimizer
- Overfitting
- Regularization

## 🟡 Supporting

- Classification
- Regression
- Clustering
- Decision Trees
- Random Forests

---

# Phase 3 — Neural Networks

> Build intelligence from the ground up.

## 🟢 Core

- Perceptron
- Artificial Neurons
- Weights
- Bias
- Hidden Layers
- Forward Pass
- Activation Functions
- Sigmoid
- tanh
- ReLU
- Softmax
- Cross Entropy Loss
- Backpropagation
- Learning Rate
- Weight Initialization

## 🟡 Supporting

- Batch Normalization
- Dropout

## ⚪ Awareness

- Convolutional Neural Networks (CNNs)
- Recurrent Neural Networks (RNNs)
- Long Short-Term Memory (LSTM)

---

# Phase 4 — Language Modeling Foundations

> Learn how computers understand text.

## 🟢 Core

- Text as Data
- Vocabulary
- Tokenization
- One-Hot Encoding
- Embeddings
- Context Windows
- Next Word Prediction
- Language Models
- Perplexity

## 🟡 Supporting

- Word2Vec
- GloVe
- Byte Pair Encoding (BPE)
- SentencePiece

---

# Phase 5 — Transformers

> Understand the architecture that changed AI.

## 🟢 Core

- Self-Attention
- Query, Key & Value
- Scaled Dot-Product Attention
- Softmax within Attention
- Multi-Head Attention
- Positional Encoding
- Feed Forward Networks
- Residual Connections
- Layer Normalization
- Transformer Blocks
- Encoder
- Decoder
- Causal Masking

## 🟡 Supporting

- Rotary Positional Embeddings (RoPE)
- Flash Attention
- KV Cache

---

# Phase 6 — Building GPT

> Assemble a complete decoder-only language model.

## 🟢 Core

- GPT Architecture
- Decoder-Only Transformers
- Autoregressive Generation
- Context Window
- Temperature Sampling
- Top-K Sampling
- Top-P Sampling
- Beam Search
- Training Loop
- Checkpointing
- Scaling Laws

## 🟡 Supporting

- Mixture of Experts (MoE)
- Speculative Decoding

---

# Phase 7 — LLM Training & Fine-Tuning

> Learn how modern LLMs are trained and adapted.

## 🟢 Core

- Data Preparation
- Pre-training
- Supervised Fine-Tuning (SFT)
- LoRA
- QLoRA
- PEFT
- RLHF
- Reward Models
- Model Evaluation
- Synthetic Data

## 🟡 Supporting

- PPO
- DPO
- GRPO

---

# Phase 8 — Efficient & Micro LLMs

> Build and optimize smaller, faster language models.

## 🟢 Core

- Quantization
- Distillation
- Pruning
- GGUF
- Model Compression
- Inference Optimization

## 🟡 Supporting

- Tensor Parallelism
- Pipeline Parallelism

---

# Phase 9 — Retrieval-Augmented Generation (RAG)

> Extend LLMs with external knowledge.

## 🟢 Core

- Embeddings for Retrieval
- Semantic Search
- Vector Databases
- Chunking Strategies
- Retrieval
- Re-ranking
- Context Injection
- Prompt Engineering
- RAG Evaluation

## 🟡 Supporting

- Hybrid Search
- Graph RAG

---

# Phase 10 — AI Agents

> Build intelligent systems that can reason and act.

## 🟢 Core

- Tool Calling
- Function Calling
- Planning
- Memory
- Reflection
- Multi-Agent Systems
- Model Context Protocol (MCP)
- Agent Evaluation

## 🟡 Supporting

- ReAct
- AutoGen
- LangGraph

---

# Phase 11 — Production AI

> Deploy reliable AI systems into production.

## 🟢 Core

- Model Serving
- APIs
- Docker
- Monitoring
- Observability
- Hallucination Detection
- Evaluation Pipelines
- Prompt Versioning
- Cost Optimization
- Caching
- Security
- AI Safety
- Responsible AI

## 🟡 Supporting

- Kubernetes
- vLLM
- TensorRT-LLM
- Ray Serve

---

# Phase 12 — AI Architecture

> Design scalable AI platforms and products.

## 🟢 Core

- AI System Design
- AI Architecture Patterns
- Multi-Tenant AI Systems
- Cost Modeling
- Latency Optimization
- Build vs Buy Decisions
- Model Selection
- Data Pipelines
- Governance
- Observability
- Scaling AI Products

---

# Capstone Projects

Each phase concludes with one or more implementation projects.

- Build a Forward Pass
- Train a Tiny Neural Network
- Build an Embedding Layer
- Implement Self-Attention
- Build a Transformer Block
- Build a Tiny GPT
- Fine-Tune a Small Language Model
- Build a Retrieval-Augmented Generation (RAG) System
- Build an AI Agent
- Deploy an AI System to Production
- Design and Build the DheniQ AI Platform

---

# Learning Philosophy

This roadmap follows a **first-principles approach**.

For every core concept, the objective is to:

1. Understand **what** it is.
2. Understand **why** it was introduced.
3. Understand **the problem it solves**.
4. Build an intuitive mental model.
5. Learn the required mathematics.
6. Implement it from scratch.
7. Experiment with different variations.
8. Understand trade-offs and limitations.
9. Connect it to modern AI systems.
10. Be able to explain and teach it confidently.

> **Master the fundamentals. Build everything from first principles. Understand before using.**