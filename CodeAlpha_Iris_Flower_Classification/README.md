# Iris Flower Classification 🌸

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-v1.0+-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

An interactive Machine Learning project built in Python to classify Iris flower species based on physical measurements of sepal and petal dimensions. Created for the **CodeAlpha Data Science Internship**.

---

## 📌 Project Overview
The objective of this project is to build and evaluate a multi-class classification model using the classic **Iris Dataset**. Using feature scaling and supervised machine learning algorithms, the model predicts whether a flower belongs to one of three species:
* `Iris-setosa`
* `Iris-versicolor`
* `Iris-virginica`

---

## 📊 Dataset Description
The dataset (`Iris.csv`) consists of **150 samples** with 4 continuous numeric features:
1. **Sepal Length** (in cm)
2. **Sepal Width** (in cm)
3. **Petal Length** (in cm)
4. **Petal Width** (in cm)

**Class Distribution:** 50 samples per species (100% balanced dataset with no missing values).

---

## 🛠️ Machine Learning Workflow
1. **Data Inspection & Cleaning:** Checked data types, shape, and null values using `Pandas`.
2. **Exploratory Data Analysis (EDA):** Visualized feature distributions and correlation relationships using `Seaborn` pairplots.
3. **Data Preprocessing:** Removed non-predictive columns (`Id`), split data into **80% Training / 20% Testing** sets, and applied `StandardScaler` feature normalization.
4. **Model Training & Comparison:** Evaluated multiple classification algorithms:
   * **Support Vector Machine (SVM)** — *Best Performing Model*
   * **Logistic Regression**
   * **K-Nearest Neighbors (KNN)**
   * **Random Forest Classifier**
5. **Evaluation:** Generated accuracy metrics, classification reports (precision, recall, f1-score), and confusion matrices.

---

## 📈 Model Performance & Results

| Model | Accuracy Score |
| :--- | :--- |
| **Support Vector Machine (SVM)** | **96.67%** |
| **Logistic Regression** | **93.33%** |
| **K-Nearest Neighbors (KNN)** | **93.33%** |
| **Random Forest** | **90.00%** |

* **Key Insight:** `PetalLengthCm` and `PetalWidthCm` provided over 86% of the predictive importance for distinguishing species.

---

## 💻 Tech Stack & Libraries
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn
* **Environment:** Jupyter Notebook / VS Code

---

## 🚀 How to Run locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/RytnixR/CodeAlpha-Intership-Data_Science-Project/tree/main/CodeAlpha_Iris_Flower_Classification.git](https://github.com/RytnixR/CodeAlpha-Intership-Data_Science-Project/tree/main/CodeAlpha_Iris_Flower_Classification.git)
   cd CodeAlpha_Iris_Flower_Classification
