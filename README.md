# Credit_Risk_Analysis

## Overview

Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

The purpose is to determine and predict credit card risk by utilizing different machine learning techniques.

## Results Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Random Oversampler
  - Balanced accuracy score: 66%
  - Precision score: 99%
  - Recall score: 62% 
  
### Synthetic minority oversampling technique (SMOTE Oversampling) 
  - Balanced accuracy score: 66%
  - Precision score: 99%
  - Recall score: 69%
  - 
### Undersampling
  - Balanced accuracy score: 66%
  - Precision score: 99%
  - Recall score: 40%
  - 
### SMOTEEN Combination
  - Balanced accuracy score: 54%
  - Precision score: 99%
  - Recall score: 58%
  - 
### Balanced Random Forest Classifier
  - Balanced accuracy score: 78%
  - Precision score: 99%
  - Recall score: 88%
  - 
### Easy Ensemble AdaBoost Classifier
  - Balanced accuracy score: 92%
  - Precision score: 99%
  - Recall score: 94%


## Summary Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
