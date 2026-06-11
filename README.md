# Decision Tree Classification Model

## Description

This project focuses on building a Classification and Regression Tree (CART) Decision Tree model to predict the presence of heart disease based on various clinical and demographic characteristics. The primary objective is to identify the most important risk factors associated with heart disease and evaluate the model’s ability to accurately classify patients as having or not having heart disease. Due to its tree-based structure, the model also provides clear interpretability, making it easier to understand the decision-making process behind predictions.

## Technologies Used

* Pandas – data manipulation and preprocessing
* NumPy – numerical computations
* Matplotlib – data visualization
* Seaborn – statistical analysis and plotting
* Scikit-learn – model development and evaluation

## Methodology

### 1. Data Preprocessing

* Missing and inconsistent values were handled where necessary.
* Relevant clinical features were selected and prepared for analysis.
* Categorical variables were encoded into numerical format when required.
* The dataset was divided into training and testing sets to evaluate model performance on unseen data.

### 2. Model Building

A CART Decision Tree Classification model was trained to predict heart disease outcomes. The model recursively splits the data into decision nodes based on the most informative features, creating a tree structure that can classify patients according to their medical characteristics.

### 3. Model Evaluation

The model performance was evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC Curve
* ROC-AUC Score

## Key Insights

* Maximum heart rate achieved is one of the most influential predictors of heart disease.
* Exercise-induced angina provides important information regarding cardiovascular health and contributes significantly to classification decisions.
* Cholesterol levels and fasting blood sugar show meaningful relationships with heart disease risk.
* Additional clinical indicators help the model distinguish between healthy and affected individuals.
* The hierarchical structure of the Decision Tree makes the prediction process highly interpretable and easy to visualize.

## Conclusion

The CART Decision Tree Classification model demonstrated strong performance in predicting heart disease and successfully captured important relationships among clinical variables. The model achieved high accuracy, precision, recall, and F1-score, indicating a balanced ability to correctly identify both positive and negative cases.

Furthermore, the ROC-AUC score of approximately 0.92 confirms that the model possesses strong discriminative power and performs significantly better than random classification. The confusion matrix and classification metrics indicate reliable generalization to unseen patient data.

Overall, the Decision Tree model provides both accurate predictions and valuable interpretability, making it an effective tool for heart disease prediction and for understanding the key medical factors associated with cardiovascular risk.
