# Credit_Risk_Analysis

## Overview

Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

The purpose is to determine and predict credit card risk by utilizing different machine learning techniques.

## Results

### Random Oversampler
  - Balanced accuracy score: 66%
  - Precision score: 99%
  - Recall score: 62% 
  
  ![Native Random Oversampling](https://user-images.githubusercontent.com/103234661/194463848-aee43227-4522-4c09-ae20-49da2a8d04d9.png)

### Synthetic minority oversampling technique (SMOTE Oversampling) 
  - Balanced accuracy score: 66%
  - Precision score: 99%
  - Recall score: 69%
  
  ![SMOTE Oversampling](https://user-images.githubusercontent.com/103234661/194463860-d1d2d16e-fb54-433e-83eb-19813dd3296b.png)

### Undersampling
  - Balanced accuracy score: 66%
  - Precision score: 99%
  - Recall score: 40%
  
  ![Undersampling](https://user-images.githubusercontent.com/103234661/194463872-f85ad930-25c8-4430-90ce-cacc2c455fd1.png)

### SMOTEEN Combination
  - Balanced accuracy score: 54%
  - Precision score: 99%
  - Recall score: 58%
  
  ![Combination (Over and Under) Sampling](https://user-images.githubusercontent.com/103234661/194463894-6fb4d874-2b6d-4cae-befd-d681a367f77e.png)

### Balanced Random Forest Classifier
  - Balanced accuracy score: 78%
  - Precision score: 99%
  - Recall score: 88%
  
  ![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/103234661/194463908-fc14f6b8-b6fe-43c9-9835-4d35acb60b9a.png)

### Easy Ensemble AdaBoost Classifier
  - Balanced accuracy score: 92%
  - Precision score: 99%
  - Recall score: 94%
  
![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/103234661/194463922-860be680-3537-4843-924c-1545db9c73dd.png)

## Summary 

We used various resampling methods (oversampling, undersampling and a combination) and while some were slightly better, they did not come close to the ensemble classifier models. My recommendation is to use the Easy Ensemble AdaBoost Classifier. It showed the best results when comparing precision scores and recall scores to the other models using various resampling models.

