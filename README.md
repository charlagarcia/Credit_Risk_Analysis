# Credit_Risk_Analysis

## Purpose
FastLending, a peer to peer lending service, wants to use machine learning to predict credit risk.  We built and evaluated several machine learning models to predict credit risk, then evaluated their performance to see how well those models predict data.

## Overview
1. Explain how a machine learning algorithm is used in data analytics.
2. Create training and test groups from a given data set.
3. Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
4. Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
5. Compare the advantages and disadvantages of each supervised learning algorithm.
6. Determine which supervised learning algorithm is best used for a given data set or scenario.
7. Use ensemble and resampling techniques to improve model performance.

## Results
### Naive Random Oversampling:
![naive](https://github.com/charlagarcia/Credit_Risk_Analysis/blob/main/Resources/Naive%20Random%20Oversampling.png)

- Balanced Accuracy: 0.645
- Precision: 0.99
- Recall: 0.66

### SMOTE Oversampling:
![smote](https://github.com/charlagarcia/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20Oversampling.png)

- Balanced Accuracy: 0.625
- Precision: 0.99
- Recall: 0.63

### Undersampling:
![under](https://github.com/charlagarcia/Credit_Risk_Analysis/blob/main/Resources/Undersampling.png)

- Balanced Accuracy: 0.515
- Precision: 0.99
- Recall: 0.46

### Combination Under-Over Sampling:
![combo](https://github.com/charlagarcia/Credit_Risk_Analysis/blob/main/Resources/Combination%20Under-Over%20Sampling.png)

- Balanced Accuracy: 0.64
- Precision: 0.99
- Recall: 0.58

### Balanced Random Forest Classifier
![forest](https://github.com/charlagarcia/Credit_Risk_Analysis/blob/main/Resources/Balanced%20Random%20Forest%20Classifier.png)

- Balanced Accuracy: 0.79
- Precision: 0.99
- Recall: 0.91

### Easy Ensemble AdaBoost Classifier:
![adaboost](https://github.com/charlagarcia/Credit_Risk_Analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier.png)

- Balanced Accuracy: 0.925
- Precision: 0.99
- Recall: 0.94

## Summary
The best machine learning model will be one with balanced acuracy (between 0 and 1) that is closest to 1. For this dataset, the Easy Ensemble AdaBoost Classifier is the best model since its balanced accuracy is 0.925 and higher than the other 5 models that are all under 0.80.  Precision for all the models were similar and within the correct parameters. The Easy Ensemble AdaBoost Classifier model had the best recall score as well, making it the overwhelming better choice for this analysis.
