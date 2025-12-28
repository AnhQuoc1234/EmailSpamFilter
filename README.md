# Spam Detection using LSTM 

This Spam Detection using LSTM(Long-short-term) to clarify ham (Non-Spam) or Spam email

## Introduction
Spam detection is a text classification . This notebook will visualize way to data processing from raw text, features selection and training model to detect spam or not spam Email.

## Dataset
Need to download `spam_ham_dataset.csv` including:
- `text`:emai/ text
- `label`: spam and ham
- `label_num`:  1 for spam, 0 for ham.

## Setting Up
To run this notebook you need to install following python extions:

```bash
pip install numpy pandas matplotlib seaborn nltk tensorflow scikit-learn wordcloud