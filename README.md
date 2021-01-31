# Credit_Risk_Analyis

## Overview of Analysis
  Credit risk is an inherently unbalanced classification problem due to good loans outnumbering risky loans.  In order to train and evaluate the models with unbalanced classes, six different machine learning methods were used:
  - ROS
  - SMOTE
  - Undersampling
  - SMOTEENN
  - Balanced Random Forest Classifier
  - Easy Ensemble Classifer
 

### Resources
- Data Source: [LoanStats_2019q1.csv](https://github.com/stephenanayashilliard/Credit_Risk_Analyis/blob/main/Resources/LoanStats_2019Q1.csv)

- Software:
 - Python 3.6.1
 - Jupyter Notebook
   - Libraries
     - Numpy
     - Pandas
     - Pathlib
     - Path
     - scipy
     - scikit-learn
     - imbalanced-learn
  - Collections
    - Counter  
 

## Results of Analysis

- ### ROS (Random Oversampling)
 
- #### Balanced Accuracy Score

![ROS_Balanced_Accuracy_score](Screenshots/ROS_Balance_Accuracy.png)

- #### Imbalanced Classification Report
![ROS_imbalanced_classification_report](Screenshots/Imbalanced_Class_Report.png)
 
- ### SMOTE (Synthetic Minority Oversampling Technique)

- #### Balanced Accuracy Score
![SMOTE_Balanced_Accuracy_score](Screenshots/Smote_Balanced_Accuracy.png)

- #### Imbalanced Classification Report
![SMOTE_classification_report](Screenshots/Smote_Imbalanced_Report.png)

- ### Undersampling

- #### Balanced Accuracy Score
![Undersampling_balanced_accuracy_score](Screenshots/Undersampling_Accuracy.png)


- #### Imbalanced Classification Report
![Undersampling_classification_report](Screenshots/Undersampling_Class_Report.png)

- ### SMOTEENN (Combined Over and Undersampling)

 - #### Balanced Accuracy Score

![SMOTEENN_balanced_accuracy_score](Screenshots/Smoteenn_Accuracy_Score.png)

- #### Imbalanced Classification Report

![SMOTEENN_classification_report](Screenshots/Smoteenn_Class_Report.png)

- ### Balanced Random Forest Classifier

- #### Balanced Accuracy Score
![BRFC_balanced_accuracy_report](Screenshots/Balanced_Random_Report.png)
- #### Imbalanced Classification Report
![BRFC_classification_report](Screenshots/Balanced_Random_Score.png)

- ### Easy Ensemble Classifier

- #### Balanced Accuracy Score
![EEC_balanced_accuracy_report](Screenshots/Easy_Score.png)
- #### Imbalanced Classification Report
![EEC_classification_report](Screenshots/Easy_Class_Report.png)

- ## Summary

s



- ### Recommendation

It is recommended that the Balanced Random Forest Classifier be used to assist in machine learning due to it having the the best Balanced Accuracy Score of 78% and the best overall Average Recall of 91%.
