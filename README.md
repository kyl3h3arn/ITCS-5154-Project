# 🧠 Breast Cancer Diagnosis with Machine Learning

This project explores and compares multiple machine learning algorithms for classifying breast cancer as benign or malignant using the **Wisconsin Breast Cancer Diagnostic (WBCD)** dataset.

Inspired by [this research paper](https://doi.org/10.1016/j.procs.2021.07.062), the project replicates and extends the study by testing additional models and evaluating their performance.

---

## 📌 Problem Statement

Breast cancer is one of the most commonly diagnosed cancers in women and a leading cause of mortality. Early detection is key to improving outcomes. This project applies machine learning to automate breast cancer classification and improve diagnostic accuracy.

---

## 🎯 Objectives

- Compare various ML algorithms for breast cancer detection.
- Replicate results from published research.
- Evaluate if newer models (e.g., XGBoost, MLP) outperform traditional ones.

---

## 🧪 Models Tested

- Support Vector Machine (SVM)
- Random Forest (RF)
- Logistic Regression (LR)
- Decision Tree (C4.5)
- K-Nearest Neighbors (KNN)
- Extreme Gradient Boosting (XGBoost) ✅ *new*
- Multi-Layer Perceptron (MLP) ✅ *new*

---

## ⚙️ Methodology

1. **Dataset:**  
   - [WBCD on Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
   - Benign = 0, Malignant = 1

2. **Preprocessing:**  
   - Removed redundant columns  
   - Normalized features  
   - Encoded target variable

3. **Evaluation Metrics:**  
   - Accuracy  
   - Precision  
   - Recall  
   - F1-Score  
   - AUC-ROC  
   - Confusion Matrix

4. **Train/Test Split:**  
   - 75% training  
   - 25% testing

---

## 📊 Results

| Algorithm           | Accuracy (%) | AUC   | Precision | Recall |
|--------------------|--------------|-------|-----------|--------|
| XGBoost            | **97.5**     | 0.970 | 0.99      | 0.96   |
| MLP                | 97.4         | 0.968 | 0.99      | 0.95   |
| SVM                | 97.2         | 0.966 | 0.98      | 0.94   |
| Random Forest      | 96.5         | 0.960 | 0.96      | 0.94   |
| Logistic Regression| 95.8         | 0.947 | 0.98      | 0.91   |
| Decision Tree      | 95.1         | 0.945 | 0.94      | 0.92   |
| KNN                | 93.7         | 0.952 | 0.92      | 0.91   |

---

## 💡 Insights

- **SVM** remained one of the top performers, consistent with published research.
- **XGBoost** slightly outperformed SVM in accuracy and precision.
- **MLP** performed strongly but may benefit from a larger dataset.
- **Feature scaling** and **hyperparameter tuning** made noticeable impacts on performance.

---

## 📈 Future Work

- Apply deep learning models to medical imaging (e.g., MRI scans)
- Test on larger and more diverse datasets
- Explore feature engineering for improved model interpretability

---

## 📚 References

1. [Procedia Computer Science, 2021](https://doi.org/10.1016/j.procs.2021.07.062)  
2. [Breast Cancer Facts & Figures 2024](https://www.cancer.org/content/dam/cancer-org/research/cancer-facts-and-statistics/breast-cancer-facts-and-figures/2024/breast-cancer-facts-and-figures-2024.pdf)  
3. Bashiri et al., 2022 - *Journal of Education and Health Promotion*  
4. [WBCD Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)  
5. Kumar & Arumugam, 2021 - *Procedia Computer Science*  
6. Kumar & Arumugam, 2023 - *Journal of Education and Health Promotion*  

---

## 🙋 Sharing Agreement

- ✅ Yes, this project can be shared with future students.
- ❌ Do not hide my name.
