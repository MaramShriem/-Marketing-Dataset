# -The tentative stages of the project

Import the Dataset

EDA( has previously provided in the "Literature Review & Data Description")

Data Preprocessing: convert y variable , shuffle the dataframe rows , Get dummies for the categorical variables, Split the Data

Modles Building:

Imbalanced Data
Random Forest Hyperparameter Tuning (based on max depth, number of trees and F1-Score)
Decision Tree Hyperparameter Tuning (based on max depth and F1-Score)
Logistic Regression Hyperparameter Tuning (based on Max Iteration, Solver and F1-Score)
1. Imbalanced-Train the model and calculate the run time of training the model
2. Imbalanced- Run Time for prediction
3. Imbalanced- Confusion Matrix
4. Imbalanced- Calculate the AUROC
5. Imbalanced- Summary (Accuracy, Recall, specificity, AUROC, MCC, Brier_score_loss, Run_time) for the models
6. Imbalanced- Check Over/Underfitting

SMOTE
1. SMOTE- Hyperparameter Tuning (based on Sampling strategy and F1-Score)
2. Data Balancing: (SMOTE)
3. SMOTE- Random Forest Hyperparameter Tuning (based on max depth, number of trees and F1-Score)
4. SMOTE- Decision Tree Hyperparameter Tuning (based on max depth and F1-Score)
3. SMOTE- Logistic Regression Hyperparameter Tuning (based on Max Iteration, Solver and F1-Score)
5. SMOTE- Train the model and calculate the run time of training the model
6. SMOTE- Run Time for prediction
7. SMOTE- Confusion Matrix
8. SMOTE- Calculate the AUROC
9. SMOTE- Summary (ACC,Recall, specificity,AUC,MCC, brier_score_loss,F1 Score, run time) for the models
10. SMOTE- Check Over/Underfitting
11. SMOTE Summary without Tuning

Random Undersampling (RUS)
1. RUS Hyperparameter Tuning (based on Sampling strategy and F1-Score)
2. Data Balancing: (Random UnderSampling)
3.RUS- Random Forest Hyperparameter Tuning (based on max depth, number of trees and F1-Score)
4. RUS- Decision Tree Hyperparameter Tuning (based on max depth and F1-Score)
3.RUS- Logistic Regression Hyperparameter Tuning (based on max Iteration, Solver, and F1-Score)
5. RUS- Train the model and calculate the run time of training the model
6. RUS- Run Time for prediction
7. RUS- Confusion Matrix
8.RUS- Calculate the AUROC
9. RUS- Summary (ACC,Recall, specificity,AUC,MCC, brier_score_loss, F1 Score, run time) for the models
10. RUS- Check Over/Underfitting
11. RUS Summary without Tuning

Random Forest Feature Importance
Decision Tree Feature Importance


Comparisons for some evaluation metrices:
Before SMOTE vs After SMOTE
Before RUS vs After RUS
SMOTE VS RUS