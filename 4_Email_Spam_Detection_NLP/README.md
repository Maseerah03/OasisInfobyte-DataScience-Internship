# Email Spam Detection using NLP and Machine Learning

## Project Overview

This project focuses on detecting spam emails using Natural Language Processing (NLP) and machine learning. A logistic regression model and a Naive Bayes classifier were implemented to classify messages as either spam or ham (non-spam).

## Dataset

The dataset used is `spam.csv`, which contains email/text messages labeled as "spam" or "ham". It includes two main columns:
- `v1` – the category (spam or ham)
- `v2` – the message content

The dataset was cleaned and reformatted for model training.

## Key Tasks Performed

- Data cleaning and preprocessing
- Label encoding (spam = 0, ham = 1)
- Text feature extraction using TF-IDF and CountVectorizer
- Train-test split of the dataset
- Model training using:
  - Logistic Regression (TF-IDF features)
  - Multinomial Naive Bayes (CountVectorizer features)
- Model evaluation using accuracy score
- Built a sample predictive system for classifying new messages

## Tools and Libraries Used

- Python
- Pandas, NumPy
- scikit-learn (TfidfVectorizer, LogisticRegression, MultinomialNB)
- CountVectorizer
- Accuracy Score

## Results

- The logistic regression model achieved strong performance on both training and test data.
- The Naive Bayes model was used for a small sample prediction to demonstrate deployment logic.
- The system successfully classified messages as spam or ham based on learned patterns.

## Conclusion

This project demonstrates how machine learning and NLP can be used to build a simple but effective email spam detection system. Text preprocessing and vectorization are critical steps in converting raw text into machine-readable input for classification models.
