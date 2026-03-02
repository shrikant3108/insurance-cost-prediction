# insurance-cost-prediction

## 📌 Problem Statement
Predict individual medical insurance charges based on demographic and lifestyle features.

## ⚙️ Algorithms Used
- Linear Regression
- Lasso Regression (L1 Regularization)
- Ridge Regression (L2 Regularization)
- LassoCV (Cross-Validation)
- RidgeCV (Cross-Validation)

## 🔧 Feature Engineering
- One-hot encoding for categorical variables
- Label mapping for binary features (sex, smoker)
- Interaction features:
  - Age × Smoker
  - BMI × Smoker
  - Children × Smoker

## 📊 Model Evaluation
- R² Score
- Mean Squared Error (MSE)
- Cross-Validation for optimal alpha selection

## 🛠 Technologies
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
