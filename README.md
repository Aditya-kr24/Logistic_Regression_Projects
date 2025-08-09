# Logistic Regression with Python

This project demonstrates how to implement Logistic Regression using Python for binary classification.  
It includes:
- Data preprocessing
- Model training
- Model evaluation using `classification_report` from scikit-learn
- Analysis of precision, recall, and F1-score

---

## **Dataset**
The dataset was split into training and testing sets, and Logistic Regression was applied to predict binary outcomes.

---

## **Results**
The model achieved an **accuracy of 78%** on the test set.

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0     | 0.78      | 0.86   | 0.82     | 154     |
| 1     | 0.78      | 0.67   | 0.72     | 114     |

**Key insights:**
- Higher recall for class 0 (0.86) compared to class 1 (0.67)
- Model performs equally well in terms of precision for both classes (0.78)
- Class imbalance slightly affects recall for class 1

---

## **Requirements**
To run the notebook, install the following:
```bash
pip install pandas numpy matplotlib scikit-learn
