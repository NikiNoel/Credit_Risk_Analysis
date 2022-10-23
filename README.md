# Credit_Risk_Analysis

## Deliverables/ Analysis

* Deliverable 1: Use Resampling Models to Predict Credit Risk
* Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
* Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
* Deliverable 4: A Written Report on the Credit Risk Analysis (README.md)

### Deliverable 1: Use Resampling Models to Predict Credit Risk
* For all three algorithms, the following have been completed:
    - An accuracy score for the model is calculated 
    - A confusion matrix has been generated 
    - An imbalanced classification report has been generated 

  **RandomOverSampler**
    - An accuracy score for the model is calculated as 0.8325
    - A confusion matrix has been generated <br>
    ![RandomOverSampler Confusion Matrix](./Images/RandomOverSampler_confusion_matrix.png)
    - An imbalanced classification report has been generated<br>
    ![RandomOverSampler Imbalanced Classification Report](./Images/RandomOverSampler_classification_report_imbalanced.png) 

 **SMOTE** <br>
- An accuracy score for the model is calculated as 0.8441 <br>
 - A confusion matrix has been generated <br>
    ![SMOTE Confusion Matrix](./Images/SMOTE_confusion_matrix.png)<br>
- An imbalanced classification report has been generated <br>
    ![SMOTE Imbalanced Classification Report](./Images/SMOTE_classification_report_imbalanced.png)

 **ClusterCentroids**<br>
- An accuracy score for the model is calculated as 0.8441<br>
 - A confusion matrix has been generated <br>
    ![ClusterCentroids Confusion Matrix](./Images/ClusterCentroids_confusion_matrix.png)<br>
- An imbalanced classification report has been generated <br>
    ![ClusterCentroids Imbalanced Classification Report](./Images/ClusterCentroids_classification_report_imbalanced.png)

## Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk 
The combinatorial SMOTEENN algorithm does the following:

**SMOTEENN**
- An accuracy score for the model is calculated to be 0.8389
- A confusion matrix has been generated <br>
![SMOTEENN Confusion Matrix](./Images/SMOTEENN_confusion_matrix.png)
- An imbalanced classification report has been generated <br>
![SMOTEENN Imbalanced Classification Report](./Images/SMOTEEN_classification_report_imbalanced.png)

## Deliverable 3 Use Ensemble Classifiers to Predict Credit Risk

* The BalancedRandomForestClassifier algorithm does the following:
- An accuracy score for the model is calculated to be 0.759
- A confusion matrix has been generated <br>
![BalancedRandomForestClassifier Confusion Matrix](./Images/BalancedRandomForestClassifier_confusion_matrix.png)
- An imbalanced classification report has been generated <br>
![BalancedRandomForestClassifier Imbalanced Classification Report](./Images/BalancedRandomForestClassifier_classification_report_imbalanced.png)
- The features are sorted in descending order by feature importance<br>
![BalancedRandomForestClassifier Feature Importance](./Images/importance_features_df.png) 

* The EasyEnsembleClassifier algorithm does the following:
    - An accuracy score of the model is calculated to be 0.9319
    - A confusion matrix has been generated <br>
![EasyEnsembleClassifier Confusion Matrix](./Images/EasyEnsembleClassifier_confusion_matrix.png)
    - An imbalanced classification report has been generated <br>
![EasyEnsembleClassifier Imbalanced Classification Report](./Images/EasyEnsembleClassifier_classification_report_imbalanced.png)
