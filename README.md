# Customer Churn Prediction Model for FP&A

## Business Problem for Finance Teams
Customer churn directly impacts Monthly Recurring Revenue (MRR) forecasts. FP&A teams need early visibility into at-risk revenue to improve forecast accuracy and support retention budgeting. This project quantifies revenue exposure from churn.

**Built for:** FP&A, Revenue Operations, CFO Office

## Tech Stack
Python, Pandas, Scikit-learn, XGBoost, Power BI for executive dashboards

## Key Results for Finance
- **Revenue at Risk Identified:** $1.2M annual revenue exposure from top 20% risk-tier customers
- **Forecast Accuracy:** Improved MRR forecast precision by predicting churn probability by customer segment
- **Automation:** Reduced monthly churn reporting time for FP&A by 40% vs manual Excel tracking
- **Model Performance:** 85% Accuracy with XGBoost vs 78% baseline Logistic Regression

## Top Churn Drivers Impacting Revenue
1. Month-to-month contracts
2. Fiber optic internet service
3. Electronic check payment method

## FP&A Use Case
Enables Finance to:
1. **Adjust revenue forecasts** based on predicted churn by segment
2. **Prioritize retention spend** by quantifying revenue impact per customer cohort
3. **Explain MRR variances** to leadership with data-driven churn insights
4. **Support board reporting** with automated risk-tier dashboards

## Files
- `analysis.ipynb`: Complete EDA, feature engineering, and model training
- `summary.pdf`: Executive summary with business recommendations for Finance
- `model_comparison.png`: ROC-AUC curves for model validation
- `risk_tiers.png`: Customer segmentation by churn probability and revenue impact
