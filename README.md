# Spam Detection using Neural Network and Word2Vec

This repository contains a Python implementation of a spam detection system using a two-layer deep neural network and Word2Vec for text classification. The system is trained on the [Spam or Not Spam Dataset](https://www.kaggle.com/datasets/ozlerhakan/spam-or-not-spam-dataset?resource=download) to classify messages as spam or not spam.

## Overview

- **Dataset**: The Spam or Not Spam Dataset is used, where each message is labeled as spam or not spam.
- **Model**: A two-layer feed-forward neural network is implemented from scratch without using any predefined neural network libraries.
- **Word Embeddings**: Word2Vec is implemented using logistic regression with negative sampling to create word embeddings.
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1 Score, and a Confusion Matrix are used to assess the model's performance.

## Contents

1. **Data Preprocessing**: Balancing the dataset and performing necessary preprocessing steps.
2. **Word2Vec Implementation**: Implementing Word2Vec using logistic regression with negative sampling to generate word embeddings.
3. **Neural Network Design**: Designing a two-layer feed-forward neural network for spam classification.
   - **Input Layer**: 12 words, each represented by a 10-dimensional embedding.
   - **Hidden Layer**: 2 nodes, each with a size of 8.
   - **Output Layer**: 1 node.
4. **Model Evaluation**: Assessing the model using accuracy, precision, recall, F1 score, and generating a confusion matrix.
