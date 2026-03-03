# Hotel Booking Analytics & Prediction System

## Project Overview

This project analyzes 119,000+ hotel booking records to:
- Predict booking cancellations
- Forecast Average Daily Rate (ADR)
- Identify seasonal and behavioral trends

The dataset includes City and Resort hotel bookings with features such as lead time, guest demographics, booking channel, deposit type, and pricing.

---

## Objectives

1. Predict cancellation likelihood using classification models.
2. Forecast ADR using regression models.
3. Analyze seasonal pricing trends.
4. Identify key drivers affecting cancellations and revenue.

---

## Models Implemented

### Classification (Cancellation Prediction)
- Random Forest (Best ROC AUC: 0.868)
- Decision Tree
- Logistic Regression

### Regression (ADR Prediction)
- Linear Regression
- Gradient Boosting
- XGBoost (Best R²: 0.864)

---

## Key Techniques

- Feature Engineering (Temporal & Behavioral Features)
- Label Encoding & Standardization
- Stratified K-Fold Cross Validation
- GridSearchCV Hyperparameter Tuning
- ROC AUC, F1-Score, RMSE, R² Evaluation

---

## Key Insights

- Lead time and deposit type strongly influence cancellations.
- ADR shows strong seasonal variation.
- Tree-based ensemble models outperform linear models.

---

## Technologies Used

- Python
- Scikit-Learn
- XGBoost
- Pandas & NumPy
- Matplotlib & Seaborn
