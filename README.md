# Bank_Customer_Churn
Classification/Prediction

## Introduction: This project involves solving a binary classification machine learning problem in the Banking and Finance industry.



## Aim: The aim of this project is to make accurate predictions from historical data in regards to whether a bank customer will churn or not.



## Methodology: While the fine details of the methodology followed in this project will be elaborated further in the relevant sections to come, it is to be mentioned that 16 standard machine learning models and 10 machine learning optimization have been implemented, compared, and contrasted to identify the best performing one.



### 01. Import CPU Python Libraries
### 02. Function Helper
### 03. Import Dataset & Data Description
- Import CSV File
- Data Description
### 04. Data Understanding
- Data Information
- Data Summary Statistic
- Data Variance
### 05. Select the Featurs
### 06. Data Pre-Processing
- Drop Variables
- Convert Data Type
- Missing Value
### 07. Exploratory Data Analysis
- DV Visualization
- Categorical IDV
- Categorical IDV With DV
- Numerical IDV
- Numerical IDV With DV
### 08. Data Transformation
- Minmax Scale
### 9. Feature Selection
- Wrapper - Forward
### 10. Feature Engineering
- LableEncoder
### 11. Statistics
- Correlations IDV with DV
- Correlation between all the Variables
### 12. Resampling Data
- SMOTE
### 13. Data Splitting
### 14. Standard Machine Learning Models
- Build the Models 'Train the Models'
- Random Forest Classifier
- Gradient Boosting Classifier
- Histogram-based Gradient Boosting Classification Tree
- AdaBoost Classifier
- Extra Trees Classifier
- K Neighbors Classifier
- Naive Bayes Classifiers
- Naive Bayes Classifier for Multivariate Bernoulli
- Decision Tree Classifier
- Logistic Regression Classifier
- Logistic Regression CV Classifier
- Stochastic Gradient Descent Classifier
- Linear Perceptron Classifier
- XGBoost Classifiers
- Support Vector Machines Classifiers
- Linear Support Vector Classification
- Multilayer Perceptron Classifier
- Predication X_test
- Models Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix
### 15. Optmization Machine Learning Models
- random grid for CPU Machine Learning Models
- Hyperparameters for CPU Machine Learning Models
- Build the Models 'Train the Models'
- Random Forest Classifier
- Gradient Boosting Classifier
- Histogram-based Gradient Boosting Classification Tree
- AdaBoost Classifier
- Extra Trees Classifier
- K Neighbors Classifier
- Decision Tree Classifier
- Logistic Regression Classifier
- Logistic Regression CV Classifier
- Stochastic Gradient Descent Classifier
- Linear Perceptron Classifier
- XGBoost Classifiers
- Support Vector Machines Classifiers
- Linear Support Vector Classification
- Predication X_test
- Models Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix
### 16. Accuracy Score Summary



## Results:



![MicrosoftTeams-image (14)](https://user-images.githubusercontent.com/108016592/175141909-cbd8cf8e-8dfc-4597-8b7c-65772a3a9f16.png)



![MicrosoftTeams-image (15)](https://user-images.githubusercontent.com/108016592/175142140-fe63687d-8674-41a5-9402-429f262044c4.png)



The results for the Standered Machine Learning it is showing XGBoost Classifiers, Histogram-based Gradient Boosting Classification Tree, Decision Tree Classifier with accuracy (89.5, 86.7, and 85.0) respectively.



![MicrosoftTeams-image (16)](https://user-images.githubusercontent.com/108016592/175142232-35693982-1e85-4867-9c71-42eeb0cf2d77.png)



![MicrosoftTeams-image (17)](https://user-images.githubusercontent.com/108016592/175142408-301c2e6c-b4f0-4518-814e-7355dbd21340.png)



The results for the Optimization Machine Learning it is showing Histogram-based Gradient Boosting Classification Tree, AdaBoost Classifier, Decision Tree Classifier with accuracy (87.2, 85.0, and 84.7) respectively.



## Discussion:



![MicrosoftTeams-image (18)](https://user-images.githubusercontent.com/108016592/175142635-93013ab5-71e7-40d4-9353-8f14e6030e49.png)



The table above provides a summary of the Accuracy of Standered CPU Models vs Accuracy of Optimization CPU Models. As it can be seen, 'Histogram-based Gradient Boosting Classification Tree', 'Random Forest Classifier', 'AdaBoost Classifier', 'K Neighbors Classifier', and 'Linear Support Vector Classification' the accuracy increased between 1% and 4% for each model.
