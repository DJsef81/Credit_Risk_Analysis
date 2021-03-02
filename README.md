# Credit_Risk_Analysis

In this module, you'll use Python to build and evaluate several machine learning models to predict credit risk. Being able to predict credit risk with machine learning algorithms can help banks and financial institutions predict anomalies, reduce risk cases, monitor portfolios, and provide recommendations on what to do in cases of fraud.

# Overview
LendingClub peer to peer lending services company wants to use machine learning to perdict credit risk. The companies management believes this will provide a quicker and more reliable loan experinece because machine learning should provide more accurate identification of good candidates for laons, leading to lower default rates. 


# Purpose of Analysis

The general task to implement this is to:
- Build and evaulate several machine learning models or algorithms to predict credit risk. 
- Use techniques such as resampling boosting to make the most of the models and data. 

However, credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. To counteract this, we will use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, we will:
- oversample the data using the RandomOverSampler and SMOTE algorithms
- Undersample the data using the ClusterCentroids algorithm
- Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm
- Compare two new machine learning models that reduce bias
- Use BalancedRandomForestClassifier and EasyEnsembleClassifier to predict credit risk. 
- Evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.


### Resources
* Python 3.7
* NumPy, version 1.19.2
* SciPy, version 1.5.2 
* Scikit-learn, version 0.23.2 

# Machine Learning Model Results 

![](https://github.com/DJsef81/Credit_Risk_Analysis/blob/main/Sampling/Naive_Random_Oversampling.png)

![](https://github.com/DJsef81/Credit_Risk_Analysis/blob/main/Sampling/SMOTE_Oversampling.png)

![](https://github.com/DJsef81/Credit_Risk_Analysis/blob/main/Sampling/Combo_Over_Under_Sampling%20.png)

![](https://github.com/DJsef81/Credit_Risk_Analysis/blob/main/Sampling/Undersampling%20.png)

![](https://github.com/DJsef81/Credit_Risk_Analysis/blob/main/Sampling/Balanced_Random_Forest_Classifier%20.png)

![](https://github.com/DJsef81/Credit_Risk_Analysis/blob/main/Sampling/Easy_Ensemble_AdaBoost_Classifier.png)

# Balanced Accuracy Score and Precision and Recall Scores of All Six Machine Learning Models

#### Naive Random Oversampling
* Precision = 0.99
* Recall = 0.56
* Balanced Accuracy = 0.64
#### SMOTE Oversampling
* Precision = 0.99
* Recall = 0.69
* Balanced Accuracy = 0.65
#### Combination (Over and Under) Sampling
* Precision = 0.99
* Recall = 0.56
* Balanced Accuracy = 0.6
#### Undersampling
* Precision = 0.99
* Recall = 0.40
* Balanced Accuracy = 0.52
#### Balanced Random Forest Classifier
* Precision = 0.99
* Recall = 0.87
* Balanced Accuracy = 0.78

#### Easy Ensemble AdaBoost Classifier 
* Precision = 0.99
* Recall = 0.87
* Balanced Accuracy = 0.78



# Summary 

# There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
