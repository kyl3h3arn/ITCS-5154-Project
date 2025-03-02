# Machine Learning Algorithms For Breast Cancer Prediction And Diagnosis

#### Kyle Hearn | ITCS 5154 Spring 2025

#### Dataset: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data
#### Paper: https://www.sciencedirect.com/science/article/pii/S1877050921014629

## Project Topic
- Bring machine learning (ML) to an area of interest <br/>
- **My Choice:** Cancer Research <br/>
- Motivation: Personal Connection, intriguing research, potential to future work. <br/>

## Project Goal
- Duplicate how others solve the problem or practice what you have learned in this course to solve the problem. <br/>
- **My Goal:** Test different ML algorithms to see which is best at predicting and/or diagnosing breast cancer. <br/>

## About

### This project aims to recreate research paper code that tests five machine learning algorithms on the Wisconsin Breast Cancer Dataset: <br/>
- Support Vector Machine (SVM)
- Random Forest
- Logistic Regression
- Decision tree (C4.5)
- K-Nearest Neighbours (KNN) <br/>
- Two additional models will be added to see if there were any improvements (TBD)

## Results
### Accuracy Comparison:
- Our results are highly consistent with the paper, particularly for SVM and Random Forest, which match exactly.
- Our Logistic Regression model performed better (97.9%) than in the paper (95.8%), indicating it generalizes slightly better on the dataset.
- Our KNN model also performed better (95.8% vs. 93.7%), suggesting possible improvements due to data preprocessing or scaling.
### AUC Comparison:
- The paper found that SVM had the highest AUC (0.966), followed by Random Forest (0.960).
- Our SVM, Random Forest, Logistic Regression, and MLP achieved perfect AUC (1.00), which suggests potential overfitting or an extremely well-separated dataset.
- Possible reasons for AUC differences:
  - Improved feature scaling or preprocessing in our implementation.
  - Different dataset splits (the paper used a 75-25% split, but variations could affect results).
### Confusion Matrix Comparison:
- The confusion matrices in our results are quite similar to the paper's results.
- SVM in both cases shows very few misclassifications, reinforcing that it is the best model for this dataset.
- Random Forest and Logistic Regression also show strong performance with minimal false positives and false negatives.
### New Model Comparison:
- XGBoost & MLP outperform Decision Tree and KNN from the paper while matching or approaching Random Forest and SVM.
- SVM still remains the best model, consistent with the paper's findings.
- XGBoost shows promise as a strong alternative to Random Forest, with similar performance but improved optimization.
  - Benefits from boosting techniques, which help reduce overfitting and improve classification.
- MLP's deep learning approach performs well, suggesting that neural networks could be useful for medical classification tasks.
  - Deep learning models like MLP may capture non-linear patterns better than Decision Trees and Logistic Regression.
  - Can be computationally expensive but works well if enough data is available.

