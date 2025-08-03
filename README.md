# LLM-compression-quantization-distillation
Efficient optimization techniques for large language models: quantization, pruning, and distillation.
# 🚀 Optimization Techniques for Large Language Models (LLMs)

This repository presents a comprehensive study and implementation overview of optimization strategies used to make large language models more efficient in terms of memory, latency, and cost — without significantly sacrificing performance.

## 🧠 Why Optimize LLMs?

Large Language Models (LLMs) such as GPT-4 and LLaMA-65B are powerful but computationally expensive. Optimization is essential for:
- Reducing inference cost and latency
- Enabling deployment on limited hardware
- Improving energy efficiency and sustainability

## 🔧 Techniques Covered

### 1. Quantization
- Post-Training Quantization (PTQ)
- Quantization-Aware Training (QAT)
- INT8, NF4, and Double Quantization (DQ)
- Implementation examples using QLoRA

### 2. Pruning
- Unstructured pruning (magnitude-based)
- Structured pruning (attention heads, FFN layers)
- Activation-aware pruning
- Discussion on sparsity and hardware constraints

### 3. Distillation
- Knowledge distillation pipeline
- Self-Instruct with synthetic data generation
- Student-teacher training loop with soft/hard targets

### 4. Mixture of Experts (MoE) *(planned section)*

## 📊 Practical Examples

- Performance analysis: FP16 vs INT8
- Case study: GPT-4 vs GPT-4 Mini
- Memory & speed benchmarks using NVIDIA H100

## 🧪 Tools & Frameworks

- PyTorch
- Huggingface Transformers
- QLoRA
- NumPy, Matplotlib
- Optuna (for tuning)

## 🔍 Research Impact

> Efficient LLM optimization is a critical step toward democratizing access to powerful AI models and ensuring their sustainability in real-world systems.

## 📚 References

- “LLM.int8(): 8-bit Matrix Multiplication for Transformers”
- “QLoRA: Efficient Finetuning of Quantized LLMs”
- “DistilBERT: Smaller, faster, cheaper and lighter”

## 👤 Author

**[Fateme Taroodi]**  
M.Sc. in Applied Mathematics – Data Science  
Shahid Beheshti University, Tehran, Iran  
Researcher in LLM Optimization, PINNs, and Reinforcement Learning  
