# NLU Assignment 2 — Word Embeddings & Name Generation

This repository contains implementations for **CSL 7640: Natural Language Understanding (Assignment 2)**.

* **Problem 1:** Word2Vec (CBOW & Skip-gram) from scratch using NumPy
* **Problem 2:** Character-level Name Generation using RNN variants (PyTorch)

---

## Files

* `problem_1.ipynb` → Word Embeddings (CBOW & Skip-gram)
* `problem_2.ipynb` → RNN, BiLSTM, Attention models

---

## Requirements

Install required libraries:

```bash
pip install numpy nltk matplotlib scikit-learn torch
```

---

## How to Run

### 🔹 Problem 1 (Word Embeddings)

```bash
jupyter notebook problem_1.ipynb
```

Run all cells sequentially to:

* preprocess data
* train CBOW & Skip-gram
* perform semantic analysis
* generate PCA & t-SNE plots

---

### 🔹 Problem 2 (Name Generation)

```bash
jupyter notebook problem_2.ipynb
```

Run all cells sequentially to:

* train RNN, BiLSTM, and Attention models
* generate names
* evaluate performance

---

## Notes

* All implementations are done from scratch
* No high-level NLP libraries (e.g., Gensim) are used
* Outputs and plots are generated within the notebooks

---
