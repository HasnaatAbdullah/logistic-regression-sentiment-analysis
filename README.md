# logistic-regression-sentiment-analysis
Implementation of logistic regression from scratch to perform sentiment analysis on tweets. Includes feature extraction, training, prediction, and error analysis using NumPy.
# 🐦 Logistic Regression for Sentiment Analysis 🧠

This repository contains my implementation of **logistic regression from scratch** to perform **sentiment analysis** on tweets.  
The model classifies tweets as **positive** or **negative** by learning from labeled data.

---

## 🚀 Project Overview
In this project, I implemented **logistic regression** step by step using **NumPy** to predict the sentiment of tweets.  
The workflow includes **data preprocessing**, **feature extraction**, **gradient descent optimization**, **prediction**, and **error analysis**.

This is a **Natural Language Processing (NLP)** task where we convert tweets into numerical features, train a classifier, and evaluate its performance.

---

## 📌 Key Features
- 🔹 Implements **logistic regression from scratch** (no TensorFlow/Keras used).
- 🔹 Performs **sentiment analysis** on tweets.
- 🔹 Uses **sigmoid activation** for binary classification.
- 🔹 Includes **feature extraction** from text.
- 🔹 Implements **gradient descent** manually for parameter optimization.
- 🔹 Performs **error analysis** on misclassified tweets.
- 🔹 Predicts sentiment for **custom user-input tweets**.

---

## 🧩 Model Architecture

| Component           | Description |
|--------------------|-------------|
| **Input**          | Tweets converted into numerical feature vectors |
| **Model**          | Logistic Regression |
| **Activation**     | Sigmoid |
| **Loss Function**  | Binary Cross-Entropy |
| **Optimizer**      | Gradient Descent |
| **Output**         | Sentiment (Positive / Negative) |

---

## 📂 Project Structure

```bash
logistic-regression-sentiment-analysis/
│── data/                     # Dataset containing tweets & labels
│── notebooks/                # Jupyter notebook implementation
│── utils/                    # Helper functions for feature extraction & processing
│── models/                   # Saved trained weights
│── results/                  # Performance reports & analysis
│── requirements.txt          # Project dependencies
└── README.md                # Documentation
