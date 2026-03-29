# 📝 T5 News Summarization Fine-Tuning (Seq2Seq Trainer)

This project implements **abstractive text summarization** using a fine-tuned T5 model with the Hugging Face Transformers framework. It demonstrates a complete pipeline from raw dataset preprocessing to model training and evaluation.

---

## 🚀 Overview

This notebook builds an end-to-end **summarization system** using T5, including:

- Data preprocessing and cleaning
- Tokenization using Hugging Face
- Fine-tuning with `Seq2SeqTrainer`
- Evaluation using ROUGE metrics
- Text generation with beam search

---

## ⚙️ Model Configuration

- Model: `t5-small` (can be switched to `t5-base`)
- Framework: PyTorch + Hugging Face Transformers
- Training API: `Seq2SeqTrainer`

---

## 🔄 Pipeline
