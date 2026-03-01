# Logistic-Regression
📊 Logistic Regression

A complete implementation and practical guide to Logistic Regression for binary classification problems using Python.

This repository covers:

Mathematical intuition

Model implementation

Assumptions

Evaluation metrics

Multicollinearity check (VIF)

Handling imbalanced datasets

🚀 Project Overview

Logistic Regression is a supervised machine learning algorithm used for classification problems, especially binary classification such as:

Fraud Detection

Spam Detection

Disease Prediction

Customer Churn Prediction

Unlike Linear Regression, Logistic Regression predicts probabilities using the sigmoid function.

📐 Mathematical Intuition

Logistic Regression models probability as:

𝑃
(
𝑦
=
1
∣
𝑋
)
=
1
1
+
𝑒
−
(
𝛽
0
+
𝛽
1
𝑋
1
+
.
.
.
+
𝛽
𝑛
𝑋
𝑛
)
P(y=1∣X)=
1+e
−(β
0
	​

+β
1
	​

X
1
	​

+...+β
n
	​

X
n
	​

)
1
	​


Where:

β = coefficients

X = features

Output range = (0, 1)

🛠️ Technologies Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Statsmodels
