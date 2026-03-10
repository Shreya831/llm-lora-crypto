# Domain-Specific LLM Fine-Tuning on Cryptography Texts

This project demonstrates fine-tuning a small GPT model (DistilGPT2) using **LoRA** for domain-specific text generation on cryptography topics.

## Features
- Fine-tunes GPT model on cryptography dataset
- Uses **LoRA** for efficient parameter tuning
- Generates domain-specific outputs
- Beginner-friendly and easy to reproduce

## Dataset
Small custom dataset of cryptography texts:
- Quantum cryptography
- RSA encryption
- Elliptic curve cryptography
- Symmetric encryption

## Training
- Tokenization using Hugging Face Transformers
- LoRA applied to attention layers for lightweight fine-tuning
- Manual training loop for causal language modeling
- Model saved locally for reuse

