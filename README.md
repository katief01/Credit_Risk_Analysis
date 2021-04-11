# Credit_Risk_Analysis

## Overview of the analysis
The purpose of this analysis was to apply machine learning to solve a real-world challenge: credit card risk. We were tasked with employing various techniques to train and evaluate models with unbalanced classes using "imbalanced-learn" and "scikit-learn" libraries. This allowed us to build and evaluate models using resampling as well as ensemble learners. The end goal was to evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

## Results 

# Naive Random Oversampling
* The balanced accuracy test for this technique is 64%, the precision for the high risk category is very low at 1%, and the recall is 66%.

<img width="720" alt="Naive_Random_OverSampling" src="https://user-images.githubusercontent.com/74223626/114289830-a9a9e400-9a40-11eb-8737-30f8c999231f.png">

# SMOTE Oversampling
* The balanced accuracy test for this technique is 65%, the precision for the high risk category is very low at 1%, and the recall is 61%.

<img width="629" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/74223626/114289860-db22af80-9a40-11eb-879a-5b577c838126.png">

# Undersampling
* The balanced accuracy test for this technique is also 65%, the precision for the high risk category is very low at 1%, and the recall is 61%.

<img width="627" alt="Undersampling" src="https://user-images.githubusercontent.com/74223626/114289872-ebd32580-9a40-11eb-94ed-9a1a709cd4d3.png">

# Combination Sampling
* The balanced accuracy test for this technique is a bit lower at 54%, the precision for the high risk category is very low at 1%, and the recall is 72%.

<img width="637" alt="Combination_Sampling" src="https://user-images.githubusercontent.com/74223626/114289879-f988ab00-9a40-11eb-9773-8e36240a70b0.png">

# Balanced Random Forest Classifier
* The balanced accuracy test for this technique is 77%, the precision for the high risk category is 3%, and the recall is 64%.

<img width="617" alt="Balanced_Random_Forest_Classifier" src="https://user-images.githubusercontent.com/74223626/114289895-0a392100-9a41-11eb-8398-046ce5584e1b.png">

# Easy Ensemble AdaBoost Classifier
* The balanced accuracy test for this technique is 93%, the precision for the high risk category is 9%, and the recall is 66%

<img width="622" alt="Easy_Ensemble_AdaBoost_Classifier" src="https://user-images.githubusercontent.com/74223626/114289904-158c4c80-9a41-11eb-8b63-ec00e03f5f38.png">

## Summary
In summary, the four techniques for resampling produced very similar results, each with very low precision and slightly above average recall and accuracy.  The two ensemble techniques produced better results with significantly higher accuracy with the AdaBoost Classifier, higher precision in both, and recalls similar to resampling. I would recommend using the AdaBoost classifier to evaluate credit card risk due to it's high accuracy score and a good balance of precision and recall scores.
