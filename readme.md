### Next Word Predictor using LSTM

This project implements a lightweight LSTM-based model for next-word prediction using a small text dataset. It efficiently tokenizes input text and generates word predictions based on a given seed phrase.

#### Features
1. Simple and optimized LSTM architecture
2. Tokenization and sequence padding for input processing
3. Efficient training on small datasets
4. Generates next-word predictions based on context

#### Requirements
Install dependencies using:
 pip install tensorflow numpy

#### Usage
Open and run the Jupyter Notebook (next-word-prediction.ipynb) step by step:

1. Load and preprocess text data
2. Train the LSTM model
3. Use predict_next_words() to generate text predictions

#### Example:
seed_text = "admit such intrusions"
generated_text = predict_next_words(model, tokenizer, seed_text, max_len=30, num_words=20)
print("Generated Text:", generated_text)
