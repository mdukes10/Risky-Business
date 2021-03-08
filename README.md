# Risky-Business

![logo](11-Machine-Learning/Instructions/Images/credit-risk.jpg)
## Background

Auto loans, mortgages, student loans, debt consolidation ... these are just a few examples of credit and loans that people are seeking online. Peer-to-peer lending services such as LendingClub or Prosper allow investors to loan other people money without the use of a bank. However, investors always want to mitigate risk, so you have been asked by a client to help them use machine learning techniques to predict credit risk.

I have build and evaluated several machine-learning models to predict credit risk using free data from LendingClub. Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans), so I have employed different techniques for training and evaluating models with imbalanced classes. I have used the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques:

1. [Resampling](#Resampling)
2. [Ensemble Learning](#Ensemble-Learning)

# Resampling 

Which model had the best balanced accuracy score?
>Smote was the best balanced accuracy score

Which model had the best recall score?
>Smote was the best recall score

Which model had the best geometric mean score?
>Both Smote and Combination Sampling had the best geometric mean score. 
# Ensemble Learning
Which model had the best balanced accuracy score?
> Easy Ensemble had the best balanced accuracy score.

Which model had the best recall score?
>Easy Ensemble had the best recall score

Which model had the best geometric mean score?
>Easy Ensemble had the best geometric mean score. 

What are the top three features?
>Top 3 features are total_rec_prncp, total_pymnt, and total_pymnt_inv.


