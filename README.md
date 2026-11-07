# Democrat vs. Republican Tweets: Political Party Classification Using NLP

## Project Overview
This project explores whether political affiliation can be identified from the language used by American politicians on Twitter.
Using a dataset of tweets from Democratic and Republican representatives, we investigate how different Natural Language Processing (NLP) techniques can be applied to political text classification.

## Research Questions
* Can political affiliation be predicted based on tweet content?
* Which text representation technique performs better: TF-IDF or Word2Vec?
* Which words and linguistic patterns are associated with each political party?
* How well does the model generalize to previously unseen politicians?

## Methodology
1. Data Preparation
* Text cleaning and normalization
* Missing value inspection
* Target variable encoding
* Train/test splitting
2. Text Representation
* TF-IDF vectorization
* Word2Vec embeddings
3. Classification
* Logistic Regression
4. Model Evaluation
* Accuracy
* Precision, Recall and F1-score
* ROC curves and ROC-AUC
* Precision-Recall curves
  
## Tools and Technologies
R, Tidyverse, Tidymodels, TextRecipes, Word2Vec, Logistic Regression, NLP, Machine Learning.

## Dataset
Democrat Vs. Republican Tweets — Kaggle.
Original dataset: https://www.kaggle.com/datasets/kapastor/democrat-vs-republican-tweets

## Limitations
The dataset reflects political communication on Twitter in 2018. The results should not be interpreted as a comprehensive representation of political ideology or voter preferences.
