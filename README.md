# SMS-Detection
This project builds a spam detection model using NLP and machine learning. It processes SMS messages, extracts features with TF-IDF, and trains classifiers to distinguish between spam and ham. The goal is to accurately identify unwanted texts through supervised learning and text preprocessing.
Overview
Spam messages are a common nuisance in communication. This project uses machine learning to build a model that can automatically identify and filter out spam SMS messages. The dataset consists of real-world SMS messages labeled as spam or ham.

Process
The dataset is cleaned and preprocessed to remove noise.

Text data is transformed into numerical features using TF-IDF vectorization.

A variety of machine learning algorithms are tested, including logistic regression, Naive Bayes, and support vector machines.

Models are evaluated using metrics like accuracy, precision, recall, and F1-score.

Goals
Build an efficient and accurate spam classifier.

Explore the impact of different preprocessing and feature extraction methods.

Evaluate the performance of multiple machine learning models.

Tools & Technologies
Python

Scikit-learn

Pandas

NLTK (for text preprocessing)

TF-IDF Vectorizer

Outcome
The final model successfully distinguishes between spam and ham messages with high accuracy, making it a useful tool for automatic SMS filtering.
