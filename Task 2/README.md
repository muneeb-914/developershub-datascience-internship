# Credit Risk Prediction

## Objective
Predict whether a loan applicant is likely to default on a loan using machine learning classification.

## Dataset
- **Source:** Kaggle — Loan Prediction Dataset
- **Shape:** 614 rows × 13 columns
- **Target:** Loan_Status (Y = Approved, N = Rejected)
- **Class Distribution:** 422 Approved (68.7%), 192 Rejected (31.3%)

## Approach
1. Analyzed and handled missing values across 7 columns
2. Performed EDA with 4 visualizations
3. Encoded categorical features using Label Encoding
4. Applied StandardScaler to normalize features
5. Trained Logistic Regression model

## Results & Insights
- **Accuracy: 78.86%**
- Model excels at identifying approvals (recall 0.99)
- Struggles with rejections (recall 0.42) due to class imbalance
- **25 false positives** — key business risk (approved applicants who may default)
- Income alone does NOT determine approval
- Graduates get approved significantly more than non-graduates

## Technologies Used
- Python, Pandas, NumPy
- Scikit-learn (Logistic Regression, StandardScaler, LabelEncoder)
- Matplotlib, Seaborn
