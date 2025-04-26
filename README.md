# Titanic-Survival-Prediction

# Objective
The goal of this project is to develop a machine learning model that predicts whether a passenger survived the Titanic disaster based on passenger details such as age, gender, ticket class, fare, and more.

# Project Overview
This repository contains:

  -> Data preprocessing steps to handle missing values, encode categorical variables, and normalize numerical data.

  -> Model training and evaluation using machine learning techniques.

  -> Analysis of model performance with metrics like accuracy, precision, and a confusion matrix.

## Steps to Run This Project
Follow these instructions to set up and run the project locally:

# 1. Clone the Repository:

bash
git clone https://github.com/your_username/titanic-survival-prediction.git
cd titanic-survival-prediction

# 2. Install Required Libraries: 
Ensure you have Python installed. Then, install the dependencies:

bash
pip install -r requirements.txt

# 3. Download the Dataset:
Ensure that the Titanic dataset (titanic.csv) is downloaded and placed in the root directory of this project.

Example dataset sources: Kaggle Titanic Dataset /www.kaggle.com/c/titanic/data

# 4. Run the Code:
Run the Python script to train the model and view results:

bash
python titanic_survival_prediction.py

# 5. Explore Results:
The script will print accuracy, precision, a classification report, and visualize the confusion matrix.

## Preprocessing Steps
The preprocessing pipeline includes:

# 1. Handling Missing Values:

  ->Imputed missing values in the 'Age' column using the median.
  ->Dropped rows with missing values in the 'Embarked' column.

# 2. Encoding Categorical Variables:

  ->One-hot encoding was applied to the 'Sex' and 'Embarked' columns to convert them into numeric forms.

# 3. Feature Scaling:
Normalized numerical columns like 'Age' and 'Fare' using StandardScaler for better model performance.

## Model Selection
A Random Forest Classifier was chosen for this task due to its efficiency with tabular datasets and strong classification performance.

The model was trained on 80% of the data and tested on the remaining 20% to evaluate its accuracy.

## Performance Analysis
The following performance metrics were used to evaluate the model:

Accuracy: Displays the percentage of correctly classified passengers.

Precision: Focuses on the accuracy of survival predictions.

Confusion Matrix: Visualizes the distribution of true positives, false positives, true negatives, and false negatives.

## Result
ccuracy: Achieved 100%.

Precision: Achieved 100% .

Confusion matrix and classification report provide detailed performance insights.
