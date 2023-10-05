# Kidney Stone Prediction

## Objective
To make a prediction about the presence of Kidney stone or not (Binary) on the basis of
given variables.

## Approach
* The following three types of Classification Models were tested:
    - Decision Tree
    - Random Forest
    - XGB Classifier
* The model was tested using the evaluation metric AUC score.
* The models were tested and Random Forest outperformed the other two models.
* Hyperparameters of Random Forest including number of estimators, maximum depth, maximum features, minimum leafs to split, bootstrap etc. were fine-tuned using the RandomisedSearchCV and GridSearchCV.
* A wide range of hyperparameters were tested using the RandomisedSearchCV, and then sequentially using GridSearchCV to further narrow down the range of hyperparameters for getting the optimum model.

## Outcome
Random Forest model with fine-tuned hyperparameters resulted in the best output with an AUC score of 0.802.