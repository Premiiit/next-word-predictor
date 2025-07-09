# 🧠 LSTM Next Word Predictor

This project implements a deep learning model to predict the **next word** in a sequence using an LSTM (Long Short-Term Memory) neural network. Built with TensorFlow/Keras and trained on a text corpus, the model learns patterns in language to generate probable next words.

---

## 📌 Overview

The notebook demonstrates the end-to-end process of building a next-word prediction model:

- Data preprocessing and tokenization
- Sequence generation for training
- Word embeddings using Keras
- LSTM-based language model
- Model evaluation and text generation

---

## 🛠️ Features

- Custom preprocessing for text cleaning
- Automatic vocabulary generation and token mapping
- Uses `Tokenizer` and `pad_sequences` from `keras.preprocessing`
- Embedding + LSTM + Dense layers
- Predicts the next word given a sentence prefix
- Plans for future integration with a **Chrome extension**

---

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Natural Language Processing (NLP)
- LSTM (Long Short-Term Memory)
- Google Colab / Jupyter Notebook

---

## 🔮 Future Scope

- Convert the model into an API using Flask or FastAPI
- Wrap predictions into a **Chrome extension** to assist users with writing
- Extend the training to larger or domain-specific corpora (e.g., news, chat, code)

---

## 📁 Project Structure

```
├── lstm_next-word-predictor.ipynb   # Main Jupyter notebook
└── README.md
```

---

## 💡 Example

Given input:  
```text
The sun rises in the
```

Predicted next word:  
```text
morning
```

---

## 🚀 How to Run

1. Install dependencies:
```bash
pip install tensorflow keras numpy
```

2. Run the notebook:
   - Train the model on the text corpus
   - Use the `predict_next_word` function to generate predictions

---

## 🤝 Contributing

Have ideas to extend this project? Feel free to fork the repo and open a PR!

---
