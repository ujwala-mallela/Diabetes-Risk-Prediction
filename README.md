# Diabetes-Risk-Prediction

## **Overview**:
This project focuses on developing a classification model to predict whether an individual has diabetes or not based on their health indicators. The dataset used for this project contains various health indicators of individuals, such as glucose levels, blood pressure, body mass index (BMI), age, etc. The goal is to build and compare multiple machine learning models to identify the most accurate and reliable approach for diabetes classification.

## Features:
The project includes the following key features:

Dataset: The project utilizes a dataset that contains a comprehensive set of health indicators for individuals, along with their diabetes status (0: No diabetes, 1: Diabetes). The dataset serves as the foundation for model development and evaluation.

Data Preprocessing: The dataset undergoes thorough preprocessing steps, including handling missing values, feature scaling, handling class imbalance, and splitting the data into training and testing sets. These steps ensure the dataset is prepared for model training and evaluation.

Logistic Regression Model: A logistic regression model is implemented to predict the presence or absence of diabetes based on the health indicators. Logistic regression is a suitable model for binary classification problems and provides insights into the influence of each feature on the target variable.

Random Forest Model: A random forest model is employed to predict diabetes status by constructing multiple decision trees on subsets of the input features. The model combines the predictions from these trees to make the final prediction. Random forests are robust to outliers, handle high-dimensional data well, and capture complex relationships between features.

Decision Tree Model: A decision tree model is implemented to identify the most important predictors of diabetes and understand how different health indicators interact to affect diabetes risk. Decision trees provide interpretable insights into the decision-making process and can uncover subgroups at increased risk for developing diabetes.

Multi-Layer Perceptron (MLP) Model: An MLP model, which is a type of artificial neural network, is utilized to capture complex relationships between the health indicators and diabetes status. MLP models are capable of modeling non-linear relationships and identifying hidden patterns in the data.

Model Evaluation: Each model's performance is evaluated using various metrics such as accuracy, classification report, mean squared error (MSE), and root mean squared error (RMSE). Additionally, confusion matrices are generated to visualize the performance of the models in terms of true positives, true negatives, false positives, and false negatives.

K-fold Cross-Validation: The models undergo k-fold cross-validation, where the dataset is divided into k subsets. Each model is trained and evaluated k times, with different subsets used as the validation set. This technique provides a more robust assessment of the models' performance and helps detect overfitting or underfitting issues.

## Screenshots
![image](https://github.com/ujwala-mallela/Diabetes-Risk-Prediction/assets/137120874/1b32abe8-81d2-410e-ad9c-001fc687d5ef)
![image](https://github.com/ujwala-mallela/Diabetes-Risk-Prediction/assets/137120874/07f415b2-5827-44f8-a61c-be73f76e7f63)
![image](https://github.com/ujwala-mallela/Diabetes-Risk-Prediction/assets/137120874/61b81994-7546-46a4-b78d-7c317dff1d59)
![image](https://github.com/ujwala-mallela/Diabetes-Risk-Prediction/assets/137120874/ef9be2e0-f4be-4e9b-aa3f-d349b55abb1f)

## Findings:

The random forest model exhibited superior performance with an accuracy of 81.33% when compared to logistic regression, MLP and decision tree models. Glucose levels, BMI, and age were consistently identified as the most influential factors in determining diabetes risk. The project's results highlight the potential of using machine learning techniques for early diabetes detection and risk assessment, which can aid in implementing preventive measures and personalized healthcare interventions.
