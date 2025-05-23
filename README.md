# 🤖 Mini Chatbot Project in Python

A Python-based chatbot that uses Natural Language Processing (NLP) and a neural network to understand and respond to user inputs. This project demonstrates how to design, train, and deploy a simple chatbot using custom intents.

---

## 🚀 Features

- Interactive chatbot for text-based queries.
- Customizable intents in `intents.json`.
- Uses Bag of Words (BoW) and one-hot encoding for NLP.
- Neural network model built with TensorFlow/Keras.
- Lightweight and easy to extend or adapt.

---

## 📁 File Structure

- `intents.json`: Predefined patterns, tags, and responses.
- `ChatBot.ipynb`: Jupyter Notebook with model training and chatbot interface.
- `README.md`: Project documentation (this file).

---

## 🧰 Requirements

Install dependencies with:

```bash
pip install tensorflow numpy nltk
```

---

## 🛠️ How to Run

1. Open `ChatBot.ipynb` in Jupyter Notebook or Google Colab.
2. Run all cells step-by-step:
   - Load data from `intents.json`
   - Preprocess text
   - Train the neural network
   - Start chatting with the bot

---

## 🔧 Customization

- Add or edit patterns/responses in `intents.json`.
- Retrain the model to reflect changes using the notebook.

---

## 🧠 How It Works

1. **Text Preprocessing**: User inputs and patterns are tokenized and transformed using Bag of Words.
2. **Model Training**: A neural network learns to classify the intent of inputs.
3. **Response Generation**: The predicted tag is used to fetch a matching response from `intents.json`.

---

## 📌 Note

This is a basic chatbot designed for educational purposes. It can be enhanced further using advanced NLP techniques like word embeddings or transformers.
