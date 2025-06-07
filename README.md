# GPT Dataset V1 — PyTorch + tiktoken Tokenizer

This project provides a simple and efficient way to create training data for GPT-style language models using PyTorch and OpenAI's `tiktoken` tokenizer (GPT-2 encoding). It supports overlapping token sequences using a sliding window, suitable for next-token prediction training.

---

## 📦 Features

- 🔁 **Sliding Window Tokenization** with `max_length` and `stride`
- ⚡ **Efficient Batching** using PyTorch `DataLoader`
- 🧠 **Next-token Target Creation** (`input_ids`, `target_ids`)
- ✂️ Customizable parameters: batch size, stride, sequence length

---

## 🛠️ Installation

```bash
pip install torch tiktoken
