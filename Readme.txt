.

📘 Fake Review Detection Using Word2Vec + Machine Learning

This repository contains a complete pipeline for detecting fake vs real product reviews using:

Word2Vec embeddings

Numeric metadata (category + rating)

Logistic Regression classifier

Custom prediction interface for new reviews

The solution is implemented in Google Colab using Python, scikit-learn, and Gensim.

🚀 Project Overview

Online platforms contain large numbers of user reviews, but many of them can be fake, biased, or generated for manipulation.
This project builds a machine learning model that detects fake reviews by combining:

✔ Word embeddings

Using Word2Vec to convert each review into a dense 100-dimensional semantic vector.

✔ Metadata features

Each review also includes:

Category

Rating

These are concatenated with text embeddings for better predictive power.

✔ Binary classifier

A Logistic Regression model is trained to classify each review as:

1 → REAL REVIEW

0 → FAKE REVIEW

The model achieves an accuracy of ~84%, with balanced precision and recall across both classes.
