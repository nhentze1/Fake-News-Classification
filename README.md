# Fake-News-Classification

This repository contains code for **distinguishing fake news from real news** in a multilingual context using a **XLM-RoBERTa Transformer**. We tune the model and evaluate its performance on English, French, and Spanish datasets.

> **Note:** Due to size and licensing constraints, datasets are not included. You need to download them from Kaggle and upload them to the notebook before running the code.

## Datasets

| Language | Dataset Link |
|----------|--------------|
| English  | [Kaggle: Fake News Classification](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification) |
| French   | [Kaggle: French Fake News Detector](https://www.kaggle.com/datasets/hgilles06/frenchfakenewsdetector) |
| Spanish  | [Kaggle: Spanish Political Fake News](https://www.kaggle.com/datasets/javieroterovizoso/spanish-political-fake-news) |

## Run the Code

You can run the notebooks directly on **Google Colab** (no setup required):

| Platform | Link |
|----------|------|
| Google Colab | [Open Notebook](https://colab.research.google.com/drive/1rFtNnskJmzKd7l1kvBP9_tOZLLPZhiPr) |

---

## Features

- Preprocessing and tokenization for multilingual text.
- Fine-tuning of XLM-RoBERTa for fake news classification.
- Evaluation metrics for model performance (accuracy, F1-score, etc.).
- Support for English, French, and Spanish datasets.

---

## Getting Started

1. Download the datasets from the links above.
2. Upload them to the Jupyter notebook or Google Colab environment.
3. Install the required packages (see `requirements.txt` if included).
4. Run the notebook cells sequentially to train and evaluate the model.

---
