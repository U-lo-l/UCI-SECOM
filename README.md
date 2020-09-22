# UCI-SECOM

### Introduction 

In this project I have taken semiconductor manufacturing dataset from UCI. The modern semiconductor manufacturing process is extremly complex and evolving every day.

The following alorithims were applied in order to reduce the dimension of 590 features.

(1) Low Variance (Varience Threshold)

(2) Logistic Regression

(3) Random Forest

(4) Support Vector Classification

(5) Linear SVC (similar to SVC but with kernel = 'linear')

(6) PCA(Principal Component Analysis)



### Dataset

Dataset used for this project is secom semiconductor manufacturing dataset from UCI machine learning repository. (http://archive.ics.uci.edu/ml/datasets/secom)
secom dataset is a classification dataset with 1567 samples and 591 attributes (590 variables and 1 class variable).


### Comparative Analysis

My base line model was logistic regression with the following accuracy.
Training - 99%
Test - 86%

It is obvious that my model is overfitting in this case.

After trying different algorithms, it was found that PCA with 50 features give the best result
Trainig - 93.33%
Test - 93.11%





