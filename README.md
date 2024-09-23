# Sentiment Analysis

## Overview
This project performs sentiment analysis on textual data to classify the sentiment as **positive**, **negative**, or **neutral**. It uses Natural Language Processing (NLP) techniques for preprocessing and a machine learning model to predict sentiment. For classification, this project uses Decision Tree and Random Forest. The model is trained on the preprocessed dataset to predict the sentiment for a customer's review.

## Table of Contents
- [Dataset](#Dataset)
- [Usage](#Usage)

## Dataset
The dataset used for this project contains text samples of a set of movie reviews from IMDB. The link for the dataset can be found [here](https://drive.google.com/file/d/1nxR07ebVNc5bSgfTQjeUcAoyoaNuuH6s/view)

## Usage
To run the sentiment analysis pipeline, please follow these instructions:
1. Clone the Repository
```bash
git clone https://github.com/khenm/sentiment-analysis.git
cd sentiment-analysis # or folder name storing the git
```
2. Run the `.ipynb` file in the folder
To compare the testing results, I have implemented 3 other different ensembling models, namely Adaboost, Gradient Boost and XGBoost to compare the score.
