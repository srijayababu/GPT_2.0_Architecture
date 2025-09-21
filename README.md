# GPT-2.0 Architecture (From Scratch in TensorFlow/Keras)

This repository is a **learning project** where I implemented the core architecture of **GPT-2** step by step using TensorFlow/Keras.
The goal is to demystify how GPT models work under the hood — from embeddings to multi-head self-attention, transformer blocks, and training for next-character prediction.

---

## ✨ Features

* Token & positional embeddings
* Multi-Head Self-Attention
* Feed Forward Network (FFN)
* Stacked Transformer Blocks
* Causal masking (ensures autoregressive prediction)
* End-to-end **mini GPT-2 style model**

---

## 📂 Project Structure

```
├── gpt2_model.py        # GPT-2.0 architecture implementation
├── train.py             # Simple training loop with toy dataset
├── dataset.py           # Character-level dataset prep
├── generate.py          # Text generation function with temperature
└── README.md            # Project documentation
```

---

## ⚡ Quick Start

### 1. Clone the repo

```bash
git clone https://github.com/srijayababu/GPT_2.0_Architecture.git
cd GPT_2.0_Architecture
```

### 2. Install dependencies

```bash
pip install tensorflow
```

### 3. Run training (toy dataset included)

```bash
python train.py
```

### 4. Generate text

```bash
python generate.py
```

---

## 📊 Example Output

After training on a small Shakespeare snippet, the model generates text like:

```
To be is ti
:
Wheo thes is and of onos se qunows ques ain:
Wherin:
Wherrutof or to:
```

(Not perfect yet 😅 but it shows the model learning patterns!)

---

## 🎯 Learning Goals

* Understand the **transformer architecture** behind GPT models
* Practice building deep learning models with TensorFlow/Keras
* Explore **text generation** with causal language modeling

---

## 🚀 Next Steps

* Train on larger datasets (e.g. Shakespeare, Wikipedia)
* Add a proper **tokenizer (BPE)** instead of character-level encoding
* Experiment with more layers, bigger vocab, and longer training

---

## 📌 Note

This repo is for **educational purposes only** — it’s a simplified GPT-2.
For real applications, check out Hugging Face’s [Transformers library](https://huggingface.co/transformers/).
