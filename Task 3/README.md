# Bank Customer Churn Prediction

## Objective
Identify customers who are likely to leave the bank so retention strategies can be applied proactively.

## Dataset
- **Source:** Kaggle — Churn Modelling Dataset
- **Shape:** 10,000 rows × 14 columns
- **Target:** Exited (0 = Stayed, 1 = Churned)
- **Class Distribution:** 7,963 Stayed (79.6%), 2,037 Churned (20.4%)

## Approach
1. Explored dataset structure and distributions
2. Performed EDA with 4 visualizations
3. Dropped irrelevant columns (RowNumber, CustomerId, Surname)
4. Encoded categorical features (Gender, Geography)
5. Applied StandardScaler normalization
6. Trained Random Forest Classifier

## Results & Insights
- **Accuracy: 86.45%**
- **Age** is the #1 churn driver (importance: 0.24)
- **Germany** has double the churn rate of France and Spain (32% vs 16%)
- High-balance customers churn more — bank is losing valuable customers
- Older customers (40-50) churn significantly more than younger ones

## Technologies Used
- Python, Pandas, NumPy
- Scikit-learn (Random Forest, StandardScaler, LabelEncoder)
- Matplotlib, Seaborn
