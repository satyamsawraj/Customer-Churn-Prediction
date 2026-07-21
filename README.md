# Customer Churn Prediction using Logistic Regression

## Objective

The objective of this project is to predict whether a customer is likely to churn using Logistic Regression.

---

## Dataset

Telco Customer Churn Dataset

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

---

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Methodology

1. Loaded the dataset using Pandas.
2. Displayed the first five records.
3. Identified numerical and categorical features.
4. Checked and handled missing values.
5. Encoded categorical variables using LabelEncoder.
6. Split the dataset into 80% training and 20% testing.
7. Built a Logistic Regression model.
8. Predicted customer churn.
9. Evaluated the model using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

---

## Results

- Accuracy: **81.48%**
- Precision: **68.42%**
- Recall: **55.76%**
- F1-Score: **61.45%**

---

## Conclusion

The Logistic Regression model successfully predicted customer churn with good accuracy. Contract type, tenure, monthly charges, and internet service usage were important factors affecting churn. Although the model performed well, more advanced machine learning techniques may further improve prediction performance.
