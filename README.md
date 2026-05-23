# Telco Customer Churn Analysis

**Business Problem**: Telecom companies lose 15-25% revenue annually to customer churn. This project builds a predictive model to identify at-risk customers for proactive retention.

**Tech Stack**: Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn

**Key Results**:
- **85% Accuracy** with XGBoost vs 78% baseline Logistic Regression
- **Top 3 Churn Drivers**: Month-to-month contracts, Fiber optic internet, Electronic check payment
- **ROI Impact**: Targeting top 20% risk-tier customers can save $1.2M annually

**Methodology**:
1. EDA on 7,000+ customer records
2. Feature engineering: tenure groups, service counts
3. Model comparison: Logistic Regression, Random Forest, SVM, XGBoost
4. Risk-tier segmentation for business action

**Files**:
- `analysis.ipynb`: Complete EDA, feature engineering, and model training
- `summary.pdf`: Executive summary with business recommendations 
- `model_comparison.png`: ROC-AUC curves for 4 models
- `risk_tiers.png`: Customer segmentation by churn probability
- `requirements.txt`: Python dependencies

**Model Performance**:
| Model | Accuracy | Precision | Recall | F1-Score |
| --- | --- | --- |
| XGBoost | 85% | 0.83 | 0.79 | 0.81 |
| Random Forest | 82% | 0.80 | 0.76 | 0.78 |
