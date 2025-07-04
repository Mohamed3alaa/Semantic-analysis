# 🧠 NLP Sentiment Classification Project

This project demonstrates a sentiment classification pipeline using state-of-the-art transformer models from the Hugging Face `transformers` library. The goal is to train a model that can classify text data into different sentiment categories (e.g., positive, negative).

## 📂 Project Structure

- `NLP_Project.ipynb`: The main Jupyter Notebook containing all code for data preprocessing, model training, and evaluation.
- `requirements.txt`: List of required Python libraries.
- `README.md`: Project overview and instructions.

## 🚀 Features

- Text preprocessing using `re` and `pandas`
- Dataset preparation using `sklearn` and Hugging Face `datasets`
- Tokenization using `BERT` tokenizer
- Fine-tuning a BERT-based transformer model for sequence classification
- Model evaluation and accuracy calculation
- Optionally deployable with Flask (Flask-Ngrok for local serving)

## 🛠️ Requirements

Install the required libraries using:

```bash
pip install transformers scikit-learn torch datasets flask-ngrok
