Spam Classifier with Naive Bayes

This project implements a classic machine learning model to classify SMS messages as spam*or ham (not spam) using the Kaggle SMS Spam Collection dataset. 
It uses TF-IDF vectorization to transform text data and a Multinomial Naive Bayes classifier to perform the classification.

Detecting spam messages automatically is crucial for email and SMS platforms to reduce 
user exposure to unwanted content, scams, and phishing attempts. This project builds a binary classifier to identify such spam messages effectively.

Features:
- Data preprocessing including handling missing values and label encoding
- Text vectorization using TF-IDF (`TfidfVectorizer`)
- Classification using Multinomial Naive Bayes (`scikit-learn`)
- Model evaluation using accuracy, F1 score, and confusion matrix visualization
- Simple function to predict if a message is spam or ham
- Clear, modular, and reproducible code
