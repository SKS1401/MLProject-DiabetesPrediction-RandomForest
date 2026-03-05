# 🩺 MLProject-DiabetesPrediction-RandomForest

## 📌 Project Overview
**DiabetesPrediction-RandomForest** is a machine learning project designed to predict whether a patient is likely to have **diabetes** based on medical diagnostic measurements. The project uses the **Pima Indians Diabetes Dataset** and applies a **Random Forest Classifier** to perform binary classification.

The system demonstrates a complete machine learning workflow including **data preprocessing, model training, prediction, and evaluation**.

---

## 🎯 Objectives
- Predict diabetes risk using patient health metrics.
- Apply **Random Forest classification** for medical data analysis.
- Demonstrate data preprocessing and model evaluation techniques.
- Provide insights into feature importance for diabetes prediction.

---

## 🗂️ Dataset Description
The project uses the **Pima Indians Diabetes Dataset**, a well-known dataset for diabetes prediction tasks.

### Key Features

| Column | Description |
|------|-------------|
| `Pregnancies` | Number of times pregnant |
| `Glucose` | Plasma glucose concentration |
| `BloodPressure` | Diastolic blood pressure (mm Hg) |
| `SkinThickness` | Triceps skin fold thickness |
| `Insulin` | 2-hour serum insulin |
| `BMI` | Body Mass Index |
| `DiabetesPedigreeFunction` | Diabetes genetic influence score |
| `Age` | Age of patient |

### Target Variable

| Column | Description |
|------|-------------|
| `Outcome` | 0 → Non-Diabetic, 1 → Diabetic |

---

## 🔧 Tools & Technologies
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **Scikit-learn**
- **Jupyter Notebook / Google Colab**

---

## 🧠 Methodology

### 1️⃣ Data Preprocessing
- Loaded the dataset and performed **Exploratory Data Analysis (EDA)**.
- Checked for missing or zero values in medical attributes.
- Prepared the dataset for modeling.
- Selected relevant numerical features.
- Applied **feature scaling using StandardScaler**.

### 2️⃣ Data Preparation
- Created **feature matrix (X)** and **target variable (y)**.
- Split the dataset into **training set and testing set**.

### 3️⃣ Model Training
- Applied **Random Forest Classifier** for diabetes prediction.
- Trained the model using the **training dataset**.
- Generated predictions for the **test dataset**.

### 4️⃣ Model Evaluation
The performance of the model was evaluated using classification metrics:

| Metric | Score |
|------|------|
| Accuracy | 0.7857 |
| Sensitivity (Recall) | 0.7442 |
| Specificity | 0.89 |

These metrics measure how well the model identifies **diabetic and non-diabetic patients**.

### 5️⃣ Prediction for New Patient
The trained model can be used to **predict diabetes risk for a new patient** by providing their medical attributes as input.

---

## 📊 Sample Outputs
- Confusion Matrix
- Accuracy Score
- Sensitivity and Specificity Calculation
- Diabetes Prediction for New Patient

---

## 🚀 Potential Applications
- 🏥 Early diabetes risk screening
- 📊 Healthcare decision support systems
- 🧠 Clinical data analysis
- 📈 Medical machine learning research

---

## ▶️ How to Run the Project


###  Run the Model in Google Colab (Recommended for Quick Start)

### Step 1: Upload notebook to Google Colab
### Step 2: Upload dataset.csv to Colab environment
### Step 3: Run all cells
