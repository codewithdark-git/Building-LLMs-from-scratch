# 🧠 Building LLMs from Scratch – A 30-Day Journey

This repository guides you through the process of building a GPT-style **Large Language Model (LLM)** from scratch using PyTorch. The structure and approach are inspired by the book ***Build a Large Language Model (From Scratch)*** by **Sebastian Raschka**.

---

## 📘 Reference Book

* **Title**: *Build a Large Language Model (From Scratch)*
* **Author**: Sebastian Raschka
* **Publisher**: Manning Publications
* **Link**: [manning.com/books/build-a-large-language-model-from-scratch](https://www.manning.com/books/build-a-large-language-model-from-scratch)

---

## 🗓️ Weekly Curriculum Overview

### 🔹 Week 1: Core Concepts of Language Modeling

* Set up your development environment and explore foundational concepts in NLP and tokenization.
* Learn how to numerically encode language, build vocabularies, and understand token embeddings.
* Grasp the importance of attention mechanisms and understand how to implement them manually.

---

### 🔹 Week 2: Building the Transformer

* Dive into the architecture of Transformer models from the ground up.
* Learn about positional encoding, residual connections, normalization, and multi-head attention.
* Construct and test a decoder-style Transformer (like GPT) with causal masking.

---

### 🔹 Week 3: Training and Optimization

* Prepare and preprocess datasets such as TinyShakespeare or WikiText.
* Create efficient data pipelines and define model training loops.
* Apply optimizer strategies, monitor model perplexity, and manage model checkpoints.

---

### 🔹 Week 4: Evaluation and Hugging Face Deployment

* Implement text generation methods including greedy and top-k sampling.
* Evaluate the model's outputs and compare them with other LLMs.
* Learn how to convert your model for Hugging Face Hub and push it live.
* Create a Hugging Face Space using Gradio to serve your model with an interactive UI.

---

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
```

---

## 📁 Project Structure

```
Building-LLMs-from-scratch/
├── notebooks/            # Weekly learning notebooks
├── models/               # Model architectures & checkpoints
├── data/                 # Preprocessing and datasets
├── hf_deploy/            # Hugging Face config & deployment scripts
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
