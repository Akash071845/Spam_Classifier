🧠 Overview

This project focuses on building a Spam Classifier that automatically identifies whether a message is spam or legitimate (ham).
By leveraging Natural Language Processing (NLP) techniques and machine learning algorithms, the model learns text patterns and linguistic features that distinguish unwanted messages from genuine communication.

The goal is to demonstrate how data-driven AI approaches can enhance digital communication security by filtering out spam and minimizing exposure to harmful content.

⚙️ Features

Text preprocessing and cleaning (removing punctuation, stopwords, etc.)

Feature extraction using TF-IDF Vectorization

Model training using multiple algorithms:

Naïve Bayes

Logistic Regression

Support Vector Machine (SVM)

Random Forest (optional for comparison)

Performance evaluation using accuracy, precision, recall, and F1-score

📂 Dataset

The dataset used is the SMS Spam Collection Dataset — a widely used corpus containing labeled SMS messages as spam or ham.

Source: UCI Machine Learning Repository

Size: 5,574 SMS messages

🔍 Workflow

Import Dataset

Preprocess Text (cleaning, tokenization, stopword removal)

Convert Text to Numerical Features using TF-IDF

Train Multiple Models and compare results

Evaluate Model Performance

Predict Spam/Ham for new messages

📊 Results

Achieved over 97% accuracy with Naïve Bayes and Logistic Regression models.

TF-IDF combined with Naïve Bayes provided the best performance for lightweight deployment.

🧩 Tech Stack

Python

Scikit-learn

Pandas / NumPy

NLTK

Matplotlib / Seaborn

