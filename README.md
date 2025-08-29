# 🎗️ Breast Cancer Classification (Decision Tree)

## 📖 Project Overview
This project uses a **Decision Tree Classifier** to predict whether a tumor is **malignant** or **benign** based on the **Breast Cancer Dataset**.  
The goal is to demonstrate preprocessing, model training, evaluation, and feature importance analysis for medical data.

---

## 📂 Dataset
- **Source**: [Kaggle - Breast Cancer Dataset](https://www.kaggle.com/datasets/wasiqaliyasir/breast-cancer-dataset)  
- **File Used**: `Breast_cancer_dataset.csv`  
- **Target Variable**: `diagnosis`  
  - Encoded: **0 = Benign**, **1 = Malignant**

---

## 🛠️ Tools & Libraries
- **Python** 🐍  
- **Pandas** → Data manipulation  
- **Scikit-learn** → Decision Tree Classifier, train/test split, metrics  
- **Matplotlib & Seaborn** → Confusion matrix visualization  
- **Joblib** → Model saving/loading  

---

## ⚙️ Steps Performed
1. **Load Dataset** from Kaggle using `kagglehub`.  
2. **Data Cleaning**:
   - Checked for missing values.  
   - Encoded `diagnosis` column (Malignant/Benign → 1/0).  
3. **Data Splitting**:
   - Training set: 70%  
   - Testing set: 30%  
4. **Model Training**:
   - Built a **Decision Tree Classifier**.  
   - Trained on training data (`x_train`, `y_train`).  
5. **Model Evaluation**:
   - Predictions on test set.  
   - **Confusion Matrix** heatmap.  
   - **Classification Report** (precision, recall, f1-score).  
6. **Feature Importance**:
   - Extracted feature importances from the trained model.  
7. **Model Saving**:
   - Saved trained model as `Decision Tree-Breast cancer` using Joblib.  

---

## 📊 Results
- **Confusion Matrix**:
- [[99 9]
  [ 4 59]]

- **Classification Report**:
- Precision (Benign): 0.96  
- Precision (Malignant): 0.87  
- Recall (Benign): 0.92  
- Recall (Malignant): 0.94  
- **Accuracy:** 92%  

✅ The model performs well, with high recall for malignant cases (important in healthcare to minimize false negatives).

---

## 🚀 How to Run
1. Clone this repository:
 ```bash
 git clone https://github.com/mennaabdalazizyahia/breast-cancer-decision-tree.git
 cd breast-cancer-decision-tree

