# Next Word Predictor using LSTM

## Overview

This project implements a **Next Word Prediction System** using **Long Short-Term Memory (LSTM)** networks. Given a sequence of words, the model predicts the most likely next word based on patterns learned from a dataset of quotes.

The project demonstrates the use of **Natural Language Processing (NLP)** and **Deep Learning** techniques such as tokenization, word embeddings, sequence generation, and recurrent neural networks.

---

## Features

* Text preprocessing and tokenization
* Sequence generation for training
* Word embedding using Keras Embedding Layer
* LSTM-based sequence modeling
* Next word prediction
* Trained on a quotes dataset
* Built using TensorFlow and Keras

---

## Tech Stack

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* NLP

---

## Dataset

The model is trained on a collection of quotes stored in `quotes.csv`.

Example:

```text
Success is not final
Failure is not fatal
The future depends on what you do today
```

---

## Project Workflow

1. Load and preprocess text data
2. Tokenize sentences
3. Create input-output sequences
4. Apply padding to obtain fixed-length sequences
5. Train an Embedding + LSTM model
6. Predict the next word for a given input sequence

---

## Model Architecture

```text
Input Layer
      ↓
Embedding Layer
      ↓
LSTM Layer
      ↓
Dense Layer (Softmax)
      ↓
Predicted Word
```

---

## Example Prediction

Input:

```text
The future depends
```

Output:

```text
on
```

---

## Installation

```bash
git clone <repository-url>
cd next-word-predictor

pip install -r requirements.txt
```

---

## Run the Project

```bash
python train.py
```

or

```bash
streamlit run app.py
```

---

## Learning Outcomes

* Sequence Modeling
* Word Embeddings
* LSTM Networks
* Text Generation
* Deep Learning for NLP
* TensorFlow/Keras Workflow

---

## Future Improvements

* Replace LSTM with GRU or Transformer models
* Train on larger datasets
* Add beam search text generation
* Deploy as a web application
* Fine-tune pretrained language models

---

## Author

Harshit Singh
B.Tech Computer Engineering, NIT Kurukshetra
GitHub: https://github.com/Harshcodeit
