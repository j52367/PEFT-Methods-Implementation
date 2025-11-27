# PEFT Methods Implementation 🚀

## 📖 Introduction
This repository contains implementations and experiments of various **Parameter-Efficient Fine-Tuning (PEFT)** methods using Hugging Face libraries.
The goal is to understand how to adapt large pre-trained models (LLMs) to downstream tasks with minimal computational resources.

## 🎯 Implemented Methods
| Method | Description | Status |
| :--- | :--- | :---: |
| **LoRA** (Low-Rank Adaptation) | Freezes pre-trained weights and injects trainable rank decomposition matrices. | ✅ |
| **Prefix Tuning** | Optimizes a sequence of continuous task-specific vectors (prefixes). | 🚧 |
| **P-Tuning** | Uses trainable prompt embeddings. | 📅 |
| **IA3** | Infused Adapter by Inhibiting and Amplifying Inner Activations. | 📅 |

## 🛠️ Tech Stack
* **Python** 3.8+
* **PyTorch**
* **Hugging Face Transformers**
* **Hugging Face PEFT**

## 📊 Experiments
(실험 결과 그래프나 표를 여기에 추가할 예정)

## 🔗 References
* [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)
* [Hugging Face PEFT Documentation](https://huggingface.co/docs/peft/index)