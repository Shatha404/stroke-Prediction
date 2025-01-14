## Stroke Prediction Using Machine Learning

### Description:
This project explores the application of machine learning models to predict the likelihood of a stroke based on health and social attributes. Stroke is a leading cause of death and disability worldwide, and the goal is to develop predictive models that can help identify individuals at risk. Three machine learning algorithms—Decision Tree (DT), Support Vector Machine (SVM), and K-Nearest Neighbors (KNN)—are designed, implemented, and evaluated for this purpose.

### Key Features:

#### Dataset:
The dataset consists of 5,110 records sourced from Kaggle. Attributes include age, gender, blood pressure, glucose levels, and lifestyle factors such as smoking and exercise habits.
#### Algorithms Used:
- Decision Tree: Enhanced through pre-pruning techniques to prevent overfitting.
- SVM: Uses a linear kernel with feature scaling for improved accuracy.
- KNN: Applied with and without the ADASYN oversampling technique to address class imbalance.
#### Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1-Score
#### Implementation:

- Data preprocessing includes scaling, handling missing values, and encoding categorical variables.
- ADASYN and SMOTE are utilized to handle class imbalance.
- Hyperparameter tuning is performed using GridSearchCV.
- Libraries used: Python, Pandas, NumPy, Scikit-learn, Matplotlib, and Seaborn.
  
#### Results:
- Decision Tree: Achieved an accuracy of 94.13% with pre-pruning.
- SVM: Delivered a recall of 76% for stroke prediction.
- KNN with ADASYN: Balanced stroke detection performance with an F1-score improvement for the minority class.
#### Conclusion:
 The project highlights the importance of handling imbalanced datasets in medical predictions. While the Decision Tree achieved the highest accuracy, SVM excelled in detecting stroke cases. KNN, combined with ADASYN, provided a balanced approach to prediction.
