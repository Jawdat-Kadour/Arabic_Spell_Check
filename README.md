# Arabic Text Preprocessing and Spelling Correction

## Overview
This project provides tools for processing Arabic text by removing diacritics, filtering out Latin characters and punctuation, and truncating long sentences for efficient model input. Additionally, it incorporates a spelling correction model trained to predict the next word in a sequence and identify spelling errors in Arabic text.

### Features
- **Text Cleaning Functions**: Remove Arabic diacritics, Latin characters, numbers, and punctuation from Arabic text.
- **Bidirectional LSTM-Based Model**: Trained for sequence prediction, using bidirectional LSTMs to predict the next word in a sequence.
- **Spelling Correction with N-grams**: Detects potential spelling errors and provides correction suggestions based on Arabic text data.

### Dataset
- **arabic_dataset_classification**: https://www.kaggle.com/datasets/alinasir1596/arabic-dataset-classification


## Prerequisites
To run this code, ensure the following dependencies are installed:
- Python 3.7 or higher
- TensorFlow (>=2.3.1)
- NumPy
- NLTK (for n-grams and tokenization)
- Other necessary libraries like `re`, `string`, and `sys`

Install the required libraries using the following command:
```bash
pip install tensorflow numpy nltk
