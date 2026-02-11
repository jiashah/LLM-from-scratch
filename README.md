# LLM-from-scratch

This project implements a **GPT-style language model from scratch using PyTorch**, following a deep dive into tokenization, bigram models, self-attention, and the full Transformer-based GPT architecture.

The model is trained on text datasets such as **Wizard of Oz** and **OpenWebText**, and supports text generation from custom prompts.

---

**Features**

- Character-level tokenizer
- Bigram language model
- Full GPT architecture implementation
- Multi-Head Self-Attention
- Positional Encoding
- Transformer Blocks
- Training & validation loop
- GPU (CUDA) support
- Model saving & loading
- Text generation from prompt
- Command-line script support

---

**What I Learned**

- How tokenizers work (character-level vs others)
- Tensors vs NumPy arrays
- Embeddings and matrix multiplication
- Gradient descent & optimizers (Adam, etc.)
- Logits, loss functions, and reshaping
- Self-attention and scaling by 1/√dk
- Transformer internals
- Pretraining vs fine-tuning
- Handling large datasets (OpenWebText)
