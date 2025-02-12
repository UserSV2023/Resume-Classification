# Resume-Classification


Overview

This project classifies resumes into predefined categories using Natural Language Processing (NLP) techniques and Machine Learning models. The goal is to automate resume screening by identifying relevant categories based on text data.

Dataset

The dataset contains resumes labeled into multiple categories.

Key features:

Category: The label assigned to each resume.

Resume Text: The raw text content of the resume.

Methodology

1. Data Preprocessing

Removed stopwords, special characters, and performed text normalization.

Applied TF-IDF Vectorization to convert text into numerical features.

2. Exploratory Data Analysis (EDA)

Analyzed category distribution with visualizations.

Created word clouds to identify key terms in each category.

Checked for class imbalances in the dataset.

3. Model Training & Evaluation

Experimented with multiple classification algorithms:

Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

Naïve Bayes

Neural Networks

Evaluated models based on accuracy, precision, recall, and F1-score.

Identified the best-performing model for deployment.

Results

The final model achieved X% accuracy (to be updated based on results).

The classification performance was optimized through hyperparameter tuning.

Future Improvements

Implement deep learning approaches such as LSTMs or Transformers.

Expand dataset with more labeled resumes for better generalization.

Deploy the model as a web-based API for real-time classification.

