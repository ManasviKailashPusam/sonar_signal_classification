# 🩺 Breast Cancer Diagnosis using Machine Learning

This project uses Machine Learning techniques to classify breast tumors as **Benign (Non-Cancerous)** or **Malignant (Cancerous)** using the **Breast Cancer Wisconsin (Diagnostic) Dataset**. The notebook covers the complete machine learning pipeline, from data preprocessing to model evaluation.

---

## 📖 Project Overview

Early detection of breast cancer significantly improves treatment success and survival rates. This project builds a classification model that predicts whether a tumor is benign or malignant based on various cell nucleus features extracted from digitized breast mass images.

The project includes:

- Data Loading
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Model Training
- Model Evaluation
- Prediction

---

## 📂 Dataset

- **Dataset Name:** Breast Cancer Wisconsin (Diagnostic) Dataset
- **File:** `breast_cancer_dataset.csv`
- **Source:** https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

### Dataset Summary

- **Total Records:** 569
- **Features:** 30 Numerical Features
- **Target Classes:**
  - **M** → Malignant
  - **B** → Benign

The features describe characteristics of cell nuclei present in breast mass images, such as:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis (EDA)

Performed:

- Dataset Overview
- Missing Value Analysis
- Statistical Summary
- Class Distribution
- Correlation Matrix
- Feature Distribution
- Data Visualization

---

## ⚙️ Data Preprocessing

- Loaded the dataset
- Removed unnecessary columns
- Checked missing values
- Encoded target labels
- Feature Scaling using **StandardScaler**
- Split data into Training and Testing sets

---

## 🤖 Machine Learning Model

The notebook implements a classification model to predict breast cancer diagnosis.

Depending on your notebook, the model may include:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

---

## 📈 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score *(if implemented)*

---

## 🚀 Workflow

```text
Dataset
   │
   ▼
Data Preprocessing
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Feature Scaling
   │
   ▼
Train-Test Split
   │
   ▼
Model Training
   │
   ▼
Prediction
   │
   ▼
Model Evaluation
```

---

## 📁 Project Structure

```text
Breast-cancer-Diagnosis/
│
├── 15_2_breast_cancer_diagnosis.ipynb
├── breast_cancer_dataset.csv
├── README.md
```

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/ManasviKailashPusam/Breast-cancer-Diagnosis.git
```

### Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
15_2_breast_cancer_diagnosis.ipynb
```

---

## 📌 Results

- Successfully classified tumors as **Benign** or **Malignant**.
- Achieved high classification accuracy.
- Demonstrated a complete end-to-end Machine Learning workflow for medical diagnosis.

---

## 🔮 Future Improvements

- Hyperparameter Tuning
- XGBoost Classifier
- LightGBM
- Cross Validation
- Feature Selection
- Model Deployment using Flask/FastAPI
- Streamlit Web Application

---

## 🎯 Learning Outcomes

- Binary Classification
- Medical Data Analysis
- Feature Engineering
- Feature Scaling
- Exploratory Data Analysis
- Machine Learning Pipeline
- Model Evaluation
- Scikit-learn Implementation

---

## 👨‍💻 Author

**Manasvi Pusam**

