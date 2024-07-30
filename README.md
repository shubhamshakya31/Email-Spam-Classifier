# Email Spam/Ham Classifier

This project is an email classification system designed to distinguish between spam and ham (non-spam) emails. The model leverages the Naive Bayes algorithm and TF-IDF vectorization for feature extraction. Throughout the project, various methods were explored, including CountVectorizer and TF-IDF vectorizer, along with different Naive Bayes variants such as GaussianNB, MultinomialNB, and BernoulliNB. The best R² score was achieved using the TF-IDF vectorizer in combination with the MultinomialNB classifier.

## Project Overview

1. **Data Cleaning**: Initial step to remove irrelevant data, correct errors, and handle missing values.

2. **Exploratory Data Analysis (EDA)**: Analyze and visualize the data to understand its distribution and characteristics.

3. **Data Preprocessing**: Transform and prepare the data for feature extraction and model training.

4. **Feature Extraction**: Use TF-IDF Vectorizer to convert the text data into numerical format, representing the importance of words.

5. **Model Training**: Train the Naive Bayes classifier, with MultinomialNB showing the best performance, to predict whether an email is spam or ham.

## Features

- **TF-IDF Vectorization**: Converts textual data into numerical vectors for model input.
- **Naive Bayes Classifier**: A probabilistic model used for classification tasks, with MultinomialNB achieving the best results.



