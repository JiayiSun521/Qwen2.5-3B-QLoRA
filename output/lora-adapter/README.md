---
base_model: Qwen/Qwen2.5-3B-Instruct
library_name: peft
---

# Qwen2.5-3B QLoRA Fine-tuned Adapter

This is a LoRA adapter fine-tuned on Qwen/Qwen2.5-3B-Instruct using QLoRA.

## Training
- Base model: Qwen/Qwen2.5-3B-Instruct
- Method: QLoRA (4-bit quantization + LoRA)
- Dataset: tatsu-lab/alpaca (500 samples)
- Epochs: 3
- Final loss: 0.42
