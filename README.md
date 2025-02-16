# Disaster Tweets Classifier

Machine learning model that classifies tweets as disaster-related or not using NLP techniques and deep learning.

## Overview

This project uses Natural Language Processing (NLP) and deep learning to analyze tweets and determine if they are about real disasters or not. The model helps distinguish between tweets about actual disasters versus tweets that just use disaster-related words.

## Dataset

The model uses the following data files:

- [train.csv](train.csv) - Training dataset
- [test.csv](test.csv) - Test dataset
- [submission.csv](submission.csv) - Model predictions in Kaggle submission format

## Model Details

The model underwent hyperparameter optimization using Keras Tuner, with the tuning results stored in the [hyperparameter_tuning](hyperparameter_tuning/) directory. The best performing model architecture and weights are saved in the trial directories.

## Usage

The complete model training pipeline and analysis can be found in [disaster-tweets-classifier.ipynb](disaster-tweets-classifier.ipynb).
