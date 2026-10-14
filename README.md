# Customer Churn Prediction

## Project Overview
This project analyzes customer churn and builds machine learning classification models to identify customers who are likely to leave a service. The objective is to support data-driven customer retention decisions.

## Business Problem
Customer churn can reduce revenue and increase customer acquisition costs. Identifying customers at risk of leaving can help businesses prioritize retention efforts.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook
- Power BI (for dashboarding, if included in this repository)

## Project Workflow
1. Data cleaning and preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature preparation and model training
4. Model evaluation and comparison
5. Identification of potential customer retention opportunities

## Models Evaluated
- Logistic Regression
- Random Forest
- XGBoost

## Model Performance

| Model | ROC-AUC | F1 Score | Precision | Recall |
|---|---:|---:|---:|---:|
| Logistic Regression | 0.86 | 0.64 | 0.52 | 0.84 |
| Random Forest | 0.85 | 0.65 | 0.56 | 0.78 |
| XGBoost | 0.85 | 0.64 | 0.55 | 0.77 |

Random Forest achieved the highest F1 score and precision among the three models, while Logistic Regression achieved the highest ROC-AUC and recall in this comparison.

## Key Takeaway
The model comparison highlights the trade-off between identifying more at-risk customers and reducing false-positive churn predictions. These insights can inform customer retention strategies.

## Dataset
This project uses the IBM Telco Customer Churn dataset. Add the original dataset source link here.

## How to Run
1. Clone or download this repository.
2. Install the required Python packages.
3. Open `customer_churn_prediction.ipynb` in Jupyter Notebook.
4. Update the dataset path if necessary.
5. Run the notebook cells in order.

## Disclaimer
This is an analytical project for educational and portfolio purposes. Model performance does not guarantee business outcomes.
