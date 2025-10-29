# 🧠 Building LLMs from Scratch – A 30-Day Journey

This repository guides you through the process of building a GPT-style **Large Language Model (LLM)** from scratch using PyTorch. The structure and approach are inspired by the book ***Build a Large Language Model (From Scratch)*** by **Sebastian Raschka**.

---

## 📘 Reference Book

* **Title**: *Build a Large Language Model (From Scratch)*
* **Author**: Sebastian Raschka
* **Publisher**: Manning Publications
* **Link**: [manning.com/books/build-a-large-language-model-from-scratch](https://www.manning.com/books/build-a-large-language-model-from-scratch)
* **Free Version**: [Github Gist](https://gist.github.com/codewithdark-git/e204e6c06546f652e76ced9d479d914e)
* **Download PDF**: [PDF Version](https://raw.github.com/codewithdark-git/Building-LLMs-from-scratch/379208ccc204218f0ffc9114464b36d96a97505e/Building%20LLMs%20From%20Scratch.pdf)
* **Resourse**: [Check the resource from where I learned.](utils/resources.md)

---

## 🗓️ Weekly Curriculum Overview

### 🔹 Week 1: Foundations of Language Models

* Set up the environment and tools.
* Learn about tokenization, embeddings, and the idea of a "language model".
* Encode input/output sequences and build basic forward models.
* Understand unidirectional processing and causal language modeling.

### 🔹 Week 2: Building the Transformer Decoder

* Explore Transformer components: attention, multi-head attention, and positional encoding.
* Implement residual connections, normalization, and feedforward layers.
* Build a GPT-style decoder-only transformer architecture.

### 🔹 Week 3: Training and Dataset Handling

* Load and preprocess datasets like TinyShakespeare.
* Implement batch creation, context windows, and training routines.
* Use cross-entropy loss, optimizers, and learning rate schedulers.
* Monitor perplexity and improve generalization.

### 🔹 Week 4: Text Generation and Deployment

* Generate text using greedy, top-k, top-p, and temperature sampling.
* Evaluate and tune generation.
* Export and convert model for Hugging Face compatibility.
* Deploy via Hugging Face Hub and Gradio Space.

---

###  Build Models

- ***FaseehGPT*** is an advanced pipeline for training a GPT-style language model specifically designed for the Arabic language. [FaseehGPT](https://github.com/alphatechlogics/FaseehGPT)

- ***Urdu-LM*** is an advanced training pipeline for building a Mixture-of-Experts (MoE) language model tailored specifically for the Urdu language, enabling more efficient, scalable, and high-quality natural language understanding and generation.. [Urdu-LM](https://github.com/codewithdark-git/Urdu-LM-MOE)

## 🛠️ Getting Started

### Prerequisites

* Python 3.8+
* PyTorch
* NumPy
* Matplotlib
* JupyterLab or Notebooks
* Hugging Face libraries: `transformers`, `datasets`, `huggingface_hub`
* `gradio` for deployment

### Installation

```bash
git clone https://github.com/codewithdark-git/Building-LLMs-from-scratch.git
cd Building-LLMs-from-scratch
pip install -r requirements.txt
````

---

## 📁 Project Structure

```
Building-LLMs-from-scratch/
├── notebooks/            # Weekly learning notebooks
├── models/               # Model architectures & checkpoints
├── data/                 # Preprocessing and datasets
├── hf_deploy/            # Hugging Face config & deployment scripts
├── theoretical/          # Podcast & theoretical discussions
├── utils/                # Helper scripts
├── requirements.txt
└── README.md
```

---

## 🚀 Hugging Face Deployment

This project includes:

* Scripts to convert the model for 🤗 Transformers compatibility
* Uploading to Hugging Face Hub
* Launching an interactive demo on Hugging Face Spaces using Gradio

You’ll find detailed instructions inside the `hf_deploy/` folder.

---

## 📚 Resources

* [Transformers Docs](https://huggingface.co/docs/transformers)
* [Hugging Face](https://huggingface.co)

---

## 📄 License

MIT License — see the `LICENSE` file for details.

