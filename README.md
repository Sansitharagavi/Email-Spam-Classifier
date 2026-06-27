# Email Spam Classifier using Machine Learning

## Overview

The Email Spam Classifier is a Machine Learning application that classifies emails as **Spam** or **Ham (Not Spam)** based on the content of the email. The project uses a real-world email dataset and applies Natural Language Processing (NLP), text preprocessing, feature extraction, model training, and evaluation techniques to build an accurate spam detection model.

## Objective

The main objective of this project is to develop a machine learning model that can accurately identify spam emails using historical email data and analyze the textual patterns that distinguish spam from legitimate emails.

## Dataset

The dataset used in this project is a combined email spam dataset containing **83,448 email records**.

### Features Used

* Label (0 = Ham, 1 = Spam)
* Email Text

### Target Variable

* Label

  * 1 = Spam
  * 0 = Ham (Not Spam)

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLTK (Natural Language Toolkit)
* Scikit-learn
* Google Colab

## Project Workflow

1. Data Collection
2. Data Exploration
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Text Preprocessing
6. Feature Extraction using TF-IDF Vectorization
7. Train-Test Split
8. Model Training using Multinomial Naive Bayes
9. Prediction and Evaluation
10. Data Visualization

## Machine Learning Algorithm

### Multinomial Naive Bayes

Multinomial Naive Bayes is a supervised machine learning algorithm widely used for text classification tasks such as spam detection and sentiment analysis. It efficiently classifies text documents by calculating the probability of each class based on word frequencies and performs exceptionally well on TF-IDF vectorized text data.

## Results

The trained model successfully classifies emails as spam or ham with high accuracy. Various evaluation metrics and visualizations were used to assess the model's performance and analyze the characteristics of spam and legitimate emails.
The trained Multinomial Naive Bayes model achieved an accuracy of approximately 97–99% on the test dataset and successfully classified spam and ham emails with high precision and recall.

## Visualizations

* Spam vs Ham Email Distribution
* Spam vs Ham Bar Chart
* Email Length Distribution
* Word Count Distribution
* Spam vs Ham Email Length Comparison
* Confusion Matrix
* Word Cloud for Spam Emails
* Word Cloud for Ham Emails

## Conclusion

This project demonstrates the complete machine learning pipeline for email spam detection, from data preprocessing and exploratory analysis to model training and evaluation. The Multinomial Naive Bayes classifier effectively distinguishes spam emails from legitimate emails, providing practical experience in Natural Language Processing (NLP), machine learning, and text classification.

## Author

**Sansitha Ragavi N**

Artificial Intelligence Internship Project
