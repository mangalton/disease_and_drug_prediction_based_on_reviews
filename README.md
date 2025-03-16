# Disease Condition Prediction Based on Drug Reviews
This repository contains a machine learning project that predicts medical conditions based on user drug reviews. By analyzing textual reviews from patients, the goal is to classify them into the correct disease condition using Natural Language Processing (NLP) and classification algorithms.

The dataset used in this project is sourced from the UCI Machine Learning Repository:

    Dataset Name: Drug Review Dataset (Drugs.com)
    Number of Instances: 215,063
    Number of Attributes: 6
    Associated Tasks: Classification, Regression, Clustering
    Date Donated: 2018-10-04

  ## Steps of NLP Pipeline
  he following steps were followed for text preprocessing and model building:
<img src="path_to_your_image/NLP_pipeline_steps.png" alt="NLP Pipeline Steps" width="600"/>

    Tokenize the sentences.
    Clean reviews:
        Remove punctuation
        Remove special characters/numbers
        Convert to lowercase
        Lemmatization
    Create Bag of Words (BoW) model to vectorize.
    Apply ML algorithms:
        Naive Bayes
        Passive Aggressive Classifier
    Create TF-IDF model to vectorize.
    Apply ML algorithms again.
    Compare the results of both vectorization techniques and classifiers.
