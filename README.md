# Vision Rag 🚀  

[![Python](https://img.shields.io/badge/python-3.9%2B-blue.svg)](https://www.python.org/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)  

**Vision Rag** is a **multimodal Retrieval-Augmented Generation (RAG)** system that combines **computer vision** and **language models** to understand, retrieve, and generate intelligent responses from images and documents.  
It leverages the **ColPali** model (`vidore/colpali-v1.2`) and integrates with **Hugging Face** + **Anthropic APIs** for advanced multimodal reasoning.  

---

## ✨ Features
- 🔎 Multimodal retrieval with **ColPali**  
- 🖼️ Supports **images, PDFs, and documents**  
- ⚡ Optimized with `bitsandbytes`, `flash-attn`, and `auto-gptq`  
- ☁️ Runs seamlessly on **Google Colab** or locally  
- 🔑 Easy integration with Hugging Face & Anthropic API keys  

---

## 📂 Project Structure
``` bash
│── ColPali_to_run final.ipynb # Main notebook
│── requirements.txt # Dependencies (optional if running on Colab)
│── README.md # Project documentation

```

---

## 🛠️ Installation  

### 🔹 Local Setup
Clone the repository:
```bash
git clone https://github.com/Sejal-07/Vision_RAG.git
cd Vision_RAG
```
Install dependencies:
```bash
pip install -r requirements.txt
```

## 📦 Requirements

The main dependencies include:
- byaldi
- claudette
- transformers (latest from Hugging Face GitHub)
- qwen-vl-utils
- flash-attn
- optimum
- auto-gptq
- bitsandbytes
- poppler-utils (system package for PDFs)

---

### 📊 Workflow

1. Load ColPali model: vidore/colpali-v1.2
2. Process documents/images (via poppler-utils).
3. Generate embeddings for retrieval.
4. Query using the RAG pipeline.
5. Produce intelligent answers using connected LLMs.

---

# 📌 Example Output

<img width="1040" height="223" alt="Screenshot 2025-09-29 193331" src="https://github.com/user-attachments/assets/47481669-7e54-4f7c-acde-54058f4fb1c4" />

# 🌟 Acknowledgements
- Hugging Face
- Anthropic
- ColPali

