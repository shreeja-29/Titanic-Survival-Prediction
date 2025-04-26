# 🛳️ Titanic Survival Prediction

## 🎯 Objective
The aim of this project is to develop a **machine learning model** that predicts whether a passenger survived the Titanic disaster. Predictions are based on key features such as:
- **Age**
- **Gender**
- **Ticket Class**
- **Fare**
- And more!

---

## 📋 Project Overview
This repository contains the following components:
- 🔄 **Data Preprocessing**:
  - Handling missing values.
  - Encoding categorical variables.
  - Normalizing numerical features.
- 🤖 **Model Training and Evaluation**:
  - Using machine learning techniques to train the model.
  - Evaluating performance through metrics like accuracy, precision, and confusion matrix.
- 📊 **Performance Analysis**:
  - Visualizing results and analyzing predictions.

---

## 🚀 Steps to Run This Project
Follow these steps to get the project up and running on your local system:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/shreeja-29/Titanic-Survival-Prediction.git
   cd Titanic-Survival-Prediction
   ```

2. **Install Required Libraries**:
   Ensure Python is installed, then install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the Dataset**:
   - Ensure that the Titanic dataset (`titanic.csv`) is downloaded and placed in the root directory of the project.
   - You can find the dataset here: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data).

4. **Run the Code**:
   - Use the following command to execute the script and train the model:
     ```bash
     python titanic_survival_prediction.py
     ```

5. **Explore Results**:
   - The script will output:
     - Accuracy and precision scores.
     - A detailed classification report.
     - A visualized confusion matrix.

---

## 🔧 Preprocessing Pipeline
The preprocessing steps include:
1. **Handling Missing Values**:
   - Imputed missing values in the `Age` column with the median.
   - Dropped rows with missing values in the `Embarked` column.
2. **Encoding Categorical Variables**:
   - Applied one-hot encoding to `Sex` and `Embarked` columns to transform them into numeric features.
3. **Feature Scaling**:
   - Normalized numerical features like `Age` and `Fare` using `StandardScaler` for enhanced model performance.

---

## 🌟 Model Selection
- The model chosen for this project is a **Random Forest Classifier**, known for its efficiency in tabular datasets.
- **Training/Testing Split**:
  - 80% of the data is used for training.
  - 20% is reserved for testing and evaluation.

---

## 📈 Performance Analysis
This project evaluates the model with the following metrics:
- ✅ **Accuracy**:
  - Displays the percentage of passengers correctly classified.
- ✅ **Precision**:
  - Indicates the accuracy of survival predictions.
- ✅ **Confusion Matrix**:
  - Visual representation of true positives, true negatives, false positives, and false negatives.

### **Results**:
- **Accuracy**: `100%` 🥳
- **Precision**: `100%` 🎉
- Detailed performance insights are provided via the confusion matrix and classification report.

---

## 🛠️ Further Improvements
To enhance this project, consider:
- Implementing **feature engineering** to create new insights from the data.
- Exploring advanced algorithms such as **Gradient Boosting Machines** or **Neural Networks**.
- Performing **hyperparameter tuning** for optimized model performance.

