# Machine Learning-Based Phishing Email Detection

This project demonstrates a machine learning approach to detect phishing emails. The notebook implements natural language processing techniques to first, preprocess the data and converting the cleaned text into numerical features using Term Frequency-Inverse Document Frequency (TF-IDF) and apply several supervised learning algorithms to evaluate model performance using metrics such as accuracy, precision, recall, and F1-score. The goal is to identify phishing emails based on a set of features extracted from email content and metadata.

# Dataset

The data has been taken from Kaggle and the link for it is https://www.kaggle.com/datasets/subhajournal/phishingemails/data. This dataset is also uploaded in the repository.

## Features

- **Machine Learning Models**:
  - Logistic Regression
  - Decision Trees
  - Random Forest
  - Support Vector Machines (SVM)
- **Data Processing**:
  - Data preprocessing including tokenization, lemmatization, stop-word removal, etc.
  - Converting the preprocessed textual into numerical features using TF-IDF.
  - Encoding the labels into numerical format using Label Encoding.
- **Model Evaluation**:
  - Accuracy, precision, recall, and F1-score metrics
  - Confusion matrix visualization
- **Visualization**:
  - Plots and charts for data distribution and model evaluation metrics
