# Spam Email Classifier (Machine Learning)

A Machine Learning project that classifies SMS messages as **Spam** or **Not Spam** using Natural Language Processing techniques.

## Project Overview
Spam messages are common in emails and SMS. This project builds a machine learning model that analyzes text messages and predicts whether they are spam.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Naive Bayes Classifier
- Matplotlib & Seaborn

## Dataset
SMS Spam Collection Dataset containing labeled messages:
- Spam
- Ham (Not Spam)

## Machine Learning Pipeline
1. Data Loading
2. Data Cleaning
3. Text Vectorization using TF-IDF
4. Train/Test Split
5. Model Training (Naive Bayes)
6. Model Evaluation
7. Custom Message Prediction

## Model Performance
Accuracy: **~98%**

Evaluation Metrics:
- Precision
- Recall
- F1-score
- Confusion Matrix

## Example Predictions
Input Message:
"Win a free iPhone now! Click this link"

Prediction:
Spam

## Future Improvements
- Try other models like Logistic Regression and SVM
- Deploy as a web app using Streamlit
- Improve preprocessing techniques
