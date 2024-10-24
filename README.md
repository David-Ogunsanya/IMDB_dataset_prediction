![image](https://github.com/user-attachments/assets/c29c2a02-14a6-49c5-bb35-68847b64341e)
IMDB Movie Review Sentiment Classification
Project Overview

This project focuses on classifying the sentiment of IMDB movie reviews as either positive or negative using natural language processing (NLP) techniques. The dataset contains 50,000 movie reviews split into a training set (25,000 reviews) and a test set (25,000 reviews).

The objective is to predict the sentiment of the reviews using various machine learning techniques.
Dataset

The dataset used in this project comes from the Stanford IMDB dataset:

    IMDB Dataset: 50,000 movie reviews for sentiment analysis, classified as either positive or negative.
    The dataset contains 25,000 highly polar movie reviews for training and 25,000 for testing.
    More information on the dataset can be found here.

Steps in the Notebook

The notebook includes the following steps and techniques:
1. Data Preprocessing

    Text Cleaning: Cleaning the review text, removing stopwords, and handling punctuation.
    Stopword Removal: Using the NLTK library to remove common English stopwords that don't add value to sentiment analysis.

2. Exploratory Data Analysis (EDA)

    Bar Charts: Visualizing the number of positive and negative reviews.
    Data Insights: Understanding the distribution of sentiments in the dataset.

3. Machine Learning Models

    Naive Bayes Classifier: Multinomial Naive Bayes from scikit-learn is applied to the sentiment classification task.
    Accuracy Evaluation: The model is evaluated using accuracy metrics on the test data.

4. Data Visualization

    Various visualizations are used to interpret the dataset and model performance, including bar plots to show the classification of reviews.

Libraries Used

    Numpy: For numerical operations.
    Pandas: For handling the dataset and dataframes.
    NLTK: For natural language processing, including stopword removal.
    Matplotlib & Seaborn: For creating visualizations.
    scikit-learn: For building and evaluating machine learning models.


