# ❤️ Heart Attack Risk Prediction

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)

## 📋 Overview
Cardiovascular diseases are the leading cause of death globally. This project analyzes 2022 CDC health indicators to predict heart attack risks.

**The Engineering Challenge:**
We didn't just train a model; we performed a comparative analysis between:
1.  **Baseline Model:** Using all available clinical features (~40 attributes).
2.  **Optimized Model:** Reduced to key risk factors (Age, Smoking, BMI, etc.) to improve computational efficiency without sacrificing sensitivity.

## ⚙️ Methodology
* **Data Cleaning:** Handling nulls and normalizing continuous variables.
* **Class Imbalance:** Applied SMOTE to ensure the model learns to detect the minority class (Positive cases).
* **Feature Selection:** Used Random Forest importance metrics to filter out noise.

## 📊 Key Results

| Metric | Full Model | Optimized Model |
| :--- | :---: | :---: |
| **Accuracy** | 9X.X% | 9X.X% |
| **Recall (Sensitivity)** | 9X.X% | 9X.X% |
![Confusion Matrix](assets/confusion_matrix.png.png)
> **Medical Focus:** We prioritized **Recall** to minimize False Negatives. In healthcare, missing a patient at risk is a critical failure.

## 📂 Project Structure
* `notebooks/01_Full_Model_Baseline.ipynb`: Initial exploration and full training.
* `notebooks/02_Optimized_Feature_Selection.ipynb`: Refined model using only top features.

## 💾 Dataset
Due to size constraints, the full processed dataset is hosted on Kaggle:
👉 **[Download Dataset from Kaggle](https://www.kaggle.com/datasets/josembm/heart-attack-risk-prediction)**

## 🚀 Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/JoseMiguelB/Heart-Attack-Risk-Prediction.git
