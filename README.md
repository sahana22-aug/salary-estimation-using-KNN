# 💼 Salary Estimation using K-Nearest Neighbors (KNN)

A Machine Learning project that predicts whether a person's salary is **greater than 50K** or **less than or equal to 50K** using the **K-Nearest Neighbors (KNN)** classification algorithm.

---

## 📌 Project Overview

This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** algorithm for salary classification. The model is trained using demographic and employment-related features from a salary dataset.

The workflow includes:

- Data Loading
- Data Preprocessing
- Feature Selection
- Data Splitting
- Model Training
- K Value Selection
- Model Prediction
- Performance Evaluation

---

## 📂 Dataset

**File:** `salary.csv`

The dataset contains employee information such as:

- Age
- Education
- Capital Gain
- Hours per Week
- Salary

### Target Variable

Salary is converted into binary values:

| Salary | Encoded Value |
|---------|---------------|
| <=50K | 0 |
| >50K | 1 |

---

## 🛠️ Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📚 Machine Learning Algorithm

### K-Nearest Neighbors (KNN)

KNN is a supervised machine learning classification algorithm that predicts the class of a new data point based on the majority class of its nearest neighbors.

The project also evaluates different values of **K** to determine the optimal number of neighbors by plotting the error rate.

---

## 📋 Project Workflow

1. Import required libraries
2. Load dataset
3. Explore dataset
4. Encode salary labels
5. Select input and output variables
6. Split dataset into training and testing sets
7. Train the KNN classifier
8. Predict test data
9. Evaluate model using:
   - Confusion Matrix
   - Accuracy Score
10. Plot Error Rate vs K Value

---

## 📊 Model Evaluation

The model performance is evaluated using:

- Confusion Matrix
- Accuracy Score

The notebook also plots the **Error Rate vs K Value** graph to help select the best K value.
