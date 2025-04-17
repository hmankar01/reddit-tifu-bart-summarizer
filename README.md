# reddit-tifu-bart-summarizer
Fine‑tuned BART for abstractive summarization of Reddit TIFU posts
# Reddit TIFU Summarization with BART

A step-by-step Jupyter Notebook that demonstrates how to fine-tune a BART sequence‑to‑sequence model on the Reddit “Today I F***ed Up” (TIFU) dataset for abstractive summarization.

---

## 🔍 Overview

This notebook will show you how to:

1. **Load & explore** the Reddit TIFU dataset via `datasets.load_dataset`  
2. **Preprocess** the text (tokenization, truncation) using a BART tokenizer  
3. **Configure & run** Hugging Face’s `Seq2SeqTrainer`  
4. **Evaluate** your model with ROUGE metrics  
5. **Visualize** training curves with Matplotlib  
6. **Generate** sample summaries with a `transformers.pipeline`

---

## 📦 Requirements

- Python 3.7+  
- 🤗 Transformers  
- 🤗 Datasets  
- 🤗 Evaluate  
- Pandas  
- Matplotlib  
- Hugging Face Hub CLI (for pushing your model)

Install with pip:

```bash
pip install transformers datasets evaluate pandas matplotlib huggingface_hub
