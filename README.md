# DS_Task_4

3 Heart Disease Prediction with Decision Tree and Random Forest
This project aims to build machine learning models for predicting the likelihood of heart disease using a dataset of various health-related attributes. Two different classification algorithms are applied: Decision Tree Classifier and Random Forest Classifier. The goal is to compare the performance of both models in predicting the target variable, which indicates the presence or absence of heart disease.

# Dataset
The dataset used for this project contains various health-related features collected from individuals, including attributes like age, sex, cholesterol levels, and more. These features are used to predict the likelihood of heart disease.

Target Variable: target (binary classification: 1 indicates the presence of heart disease, 0 indicates no heart disease).

Features: Various medical attributes such as age, sex, blood pressure, cholesterol levels, etc.

# Models Used
1. Decision Tree Classifier
A Decision Tree is a supervised machine learning algorithm that splits the dataset into subsets based on feature values. It recursively creates branches that represent decisions, making it easy to visualize and interpret.

2. Random Forest Classifier
Random Forest is an ensemble method that creates a collection (forest) of decision trees. Each tree is trained on a random subset of the data, and the final prediction is made by combining the predictions from all the trees in the forest. Random Forest helps to overcome overfitting issues typically found in decision trees by averaging the results of multiple trees.

# Steps Involved
Data Loading: The dataset is loaded from a CSV file. The data contains both feature columns (e.g., age, cholesterol) and the target column (target).

Target Variable Encoding: The target variable is encoded into numerical values (0 or 1) using a LabelEncoder, as most machine learning algorithms require numerical data.

Feature and Label Preparation: The features (X) are separated from the target variable (y). This is followed by splitting the dataset into training and testing sets using an 80/20 split.

Model Training:

The Decision Tree classifier is trained on the training set.

The Random Forest classifier is trained on the same training set.

Prediction and Evaluation:

The models make predictions on the test set.

The accuracy score and classification report (precision, recall, f1-score) are computed to evaluate and compare the performance of the models.

# Conclusion
This project demonstrates the effectiveness of Decision Tree and Random Forest algorithms in predicting heart disease. By comparing the performance of these models, we can determine which one performs better and potentially use it for real-world applications in healthcare for early detection of heart disease.
