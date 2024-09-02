# Breast-Cancer-Wisoncsin-Classification-Project

# Breast Cancer Classification Project

This project aims to classify breast cancer tumors as malignant or benign using various machine learning models. The classification is based on features computed from digitized images of fine needle aspirates (FNA) of breast masses, which describe the characteristics of the cell nuclei.

## Project Overview

This is a group project conducted as part of the coursework for the **Longo Faculty of Business - Humber College**. The study involves the application and evaluation of six different machine learning models to classify breast cancer tumors. These models are:

- **Logistic Regression**
- **Naive Bayes**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- **Random Forest**
- **Gradient Boosting**

The performance of these models is evaluated using metrics such as accuracy, precision, recall, F1-score, ROC curves, and precision-recall curves.

## Team Members

- **Ornab Olindo** (Student ID: N01533188)
- **Irem Midillic** (Student ID: N01562987)
- **Yash Rajesh Doshi** (Student ID: N01597522)
- **Sakshi Singh** (Student ID: N01597828)
- **Yash Dhawan** (Student ID: N01597517)

## Faculty Supervisor

- **Sarama Shehmir**  
  Longo Faculty of Business - Humber College

## Methodology

### 1. **Dataset and Preprocessing**
- **Breast Cancer Wisconsin (Diagnostic) Data Set**: This dataset consists of 569 samples with 30 features each, derived from digitized images of FNA of breast masses.
- **Data Preprocessing**: 
  - Unnecessary columns causing multicollinearity were removed.
  - Outliers were detected and eliminated.
  - The target variable 'diagnosis' was encoded as 1 for malignant and 0 for benign.

### 2. **Models Used**
- **Logistic Regression**: A linear model used for binary classification.
- **Naive Bayes**: A probabilistic classifier based on Bayes' Theorem.
- **K-Nearest Neighbors (KNN)**: An instance-based learning algorithm that classifies data points based on the majority class of its nearest neighbors.
- **Decision Tree**: A tree-structured model that makes decisions based on feature values.
- **Random Forest**: An ensemble method that builds multiple decision trees and combines their outputs.
- **Gradient Boosting**: An ensemble technique that builds models sequentially, with each new model focusing on errors made by previous ones.

### 3. **Evaluation Metrics**
- **Accuracy**: Proportion of correctly classified samples.
- **Precision**: Proportion of true positives out of total predicted positives.
- **Recall**: Proportion of true positives out of actual positives.
- **F1-score**: Harmonic mean of precision and recall.
- **ROC Curves**: Plots the true positive rate against the false positive rate.
- **Precision-Recall Curves**: Plots precision against recall.

## Results

- **Logistic Regression**: Achieved an accuracy of 94.74%, with strong generalization capabilities.
- **Naive Bayes**: Showed good performance with an accuracy of 93.86%.
- **K-Nearest Neighbors (KNN)**: After tuning, achieved an accuracy of 92.11%.
- **Decision Tree**: Showed lower performance with an accuracy of 90.35%, prone to overfitting.
- **Random Forest**: Emerged as the best-performing model with an accuracy of 94.74%.
- **Gradient Boosting**: Achieved near-perfect accuracy of 94.74%, with excellent precision and recall.

## Conclusion

- **Best Overall Model**: Random Forest, due to its balanced performance and strong generalization.
- **Best Model Based on F1 Score**: Gradient Boosting, due to its high precision and recall balance.
- **Least Performing Model**: Decision Tree, which showed the lowest accuracy and F1 score.

## Future Work

- **Feature Engineering**: Explore interaction and polynomial features to capture complex relationships.
- **Hybrid Models**: Combine different types of models to leverage their strengths.
- **Model Explainability**: Use tools like SHAP or LIME to interpret model decisions.

## Ethical Considerations

- Addressed the potential biases, transparency, accountability, and privacy concerns associated with using machine learning for medical diagnosis.

## References

- [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- Additional datasets and references as listed in the project document.

