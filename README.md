# Diabetes Prediction using K-Nearest Neighbors (KNN)

## 📌 Project Overview

This project implements the **K-Nearest Neighbors (KNN)** classification algorithm to predict whether a patient has diabetes based on various medical diagnostic measurements. The model is trained using the **diabetes.csv** dataset and evaluated using multiple classification metrics to measure its predictive performance.

The project demonstrates the complete machine learning workflow, including data preprocessing, feature scaling, model training, prediction, and performance evaluation.

---

## 🎯 Objectives

- Load and explore the diabetes dataset
- Perform data preprocessing
- Separate features and target variable
- Split the dataset into training and testing sets
- Normalize the feature values
- Implement the K-Nearest Neighbors (KNN) classifier
- Predict diabetes outcomes
- Compute the Confusion Matrix
- Evaluate the model using Accuracy, Error Rate, Precision, and Recall

---

## 📂 Dataset

**Dataset:** Diabetes Dataset

https://www.kaggle.com/datasets/abdallamahgoub/diabetes

The dataset contains the following attributes:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (Target Variable)

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Project Structure

```
Diabetes-KNN/
│
├── 5.ipynb
├── README.md
└── diabetes.csv
```

---

## ⚙️ Project Workflow

### 1. Data Preprocessing

- Loaded the diabetes dataset
- Checked dataset information
- Verified missing values
- Explored feature distributions
- Prepared the data for machine learning

---

### 2. Feature Selection

- Selected independent variables (X)
- Selected target variable (Outcome)

---

### 3. Train-Test Split

- Split the dataset into training and testing sets
- Used Scikit-learn's `train_test_split()` function

---

### 4. Feature Scaling

Since KNN is a distance-based algorithm, feature scaling was performed using **StandardScaler** to normalize all numerical features.

---

### 5. K-Nearest Neighbors (KNN)

Implemented the **KNN Classifier** with:

- Euclidean Distance
- User-defined value of **K**
- Uniform voting

The trained model predicts whether a patient is diabetic or non-diabetic based on its nearest neighbors.

---

## 📊 Model Evaluation

The model was evaluated using:

- Confusion Matrix
- Accuracy Score
- Error Rate
- Precision
- Recall
- Classification Report


::contentReference[oaicite:0]{index=0}


---

## 📈 Results

| Metric | Description |
|---------|-------------|
| Accuracy | Overall prediction performance |
| Error Rate | Percentage of incorrect predictions |
| Precision | Correct positive predictions among all predicted positives |
| Recall | Ability to correctly identify diabetic patients |
| Confusion Matrix | Displays True Positive, True Negative, False Positive, and False Negative values |

The KNN model provides a simple and effective approach for diabetes prediction, especially when the input features are properly normalized.

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/Diabetes-KNN.git
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
5.ipynb
```

Run all cells sequentially.

---

## 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

---

## 📚 Machine Learning Pipeline

```
Dataset
    │
    ▼
Data Preprocessing
    │
    ▼
Feature Selection
    │
    ▼
Train-Test Split
    │
    ▼
Feature Scaling
    │
    ▼
K-Nearest Neighbors (KNN)
    │
    ▼
Prediction
    │
    ▼
Confusion Matrix
    │
    ▼
Accuracy
Error Rate
Precision
Recall
```

---

## 📌 Learning Outcomes

- Binary Classification
- Data Preprocessing
- Feature Scaling
- K-Nearest Neighbors (KNN)
- Euclidean Distance
- Confusion Matrix Interpretation
- Accuracy, Precision, and Recall
- Model Evaluation using Scikit-learn

---

## 👩‍💻 Author

**Sukhada Tamboli**

Interested in:

- Data Science
- Machine Learning
- Artificial Intelligence
- Deep Learning
- Python Development

---
