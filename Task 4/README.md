# Insurance Charges Prediction

## Objective
Estimate medical insurance claim amounts based on personal data such as age, BMI, and smoking status using Linear Regression.

## Dataset
- **Source:** Kaggle — Medical Cost Personal Dataset
- **Shape:** 1,338 rows × 7 columns
- **Target:** charges (medical insurance cost in USD)
- **Range:** $1,121 to $63,770

## Approach
1. Explored dataset structure and distributions
2. Performed EDA with 4 visualizations
3. Encoded categorical features (sex, smoker, region)
4. Trained Linear Regression model
5. Evaluated using MAE and RMSE

## Results & Insights
- **R² Score: 0.7833** — model explains 78.33% of charge variation
- **MAE: $4,186** — average prediction error
- **RMSE: $5,799** — penalizes larger errors
- Smokers pay **5x more** than non-smokers on average
- BMI + smoking is the most dangerous combination — charges reach $60,000+
- Age increases charges gradually but smoking status creates a massive jump

## Technologies Used
- Python, Pandas, NumPy
- Scikit-learn (Linear Regression, LabelEncoder)
- Matplotlib, Seaborn
