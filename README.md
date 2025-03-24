# Proactive Churn Prediction for a Telecom Provider

This repository presents an end-to-end analytics solution for predicting customer churn in the telecom sector and developing targeted retention strategies. The goal is to proactively identify high-risk customers and implement personalized offers to reduce churn and maximize customer lifetime value (CLV).

## Background

Telecom companies face significant losses from customer churn. Traditionally, many providers focus on **reactive churn management**, offering discounts or perks only after customers threaten to leave. This project explores a **proactive churn management** strategy by using historical customer data to predict churn risk before customers attempt to cancel.

A data sample was prepared with customer-level information covering usage, billing trends, device attributes, service issues, and customer behavior over a recent four-month period. The project includes churn prediction modeling, business insight generation, strategy simulation, and CLV-based profitability analysis.

## Objectives

1. Develop a machine learning model to predict the probability of churn.
2. Identify key drivers of churn using variable importance and interpretability methods.
3. Design targeted actions, offers, or incentives based on driver analysis.
4. Simulate the estimated impact of each action on churn probability.
5. Match the most appropriate intervention to customer segments.
6. Evaluate the economic impact of each intervention using a 5-year CLV framework.

## Data Overview

The dataset includes:

- **27,300 records for model training**
- **11,700 records for testing**
- **30,000 records in a representative sample (realistic churn rate: 2%)**

### Key Variable Categories:
- **Customer Usage:** Revenue, minutes, roaming, overages, etc.
- **Customer Actions:** Calls to customer care or retention team
- **Device Characteristics:** Smartphone vs non-smartphone, refurbished status, days since acquisition
- **Customer Attributes:** Credit rating, vehicle ownership, international travel, region
- **Churn Indicator:** Binary variable indicating churn in the last 30 days

## Methods Used

- Logistic Regression (baseline model)
- Random Forest
- XGBoost
- Model evaluation using AUC, confusion matrix, lift/gains curves
- Permutation Importance and Partial Dependence Plots for feature interpretation
- Simulation of impact from business interventions
- 5-year CLV calculation under various incentive cost assumptions

## Insights and Strategic Actions

The model identifies several actionable drivers of churn, such as:
- High customer service call volume
- Older or refurbished equipment
- Decreasing usage over time
- International roaming activity
- Length of time with current handset

From these insights, the project proposes **five retention strategies**, including early handset upgrades, proactive outreach to high-service callers, and roaming discount offers. Each is matched to customers based on model-predicted churn drivers and quantified using churn reduction impact and CLV thresholds.

## Project Structure

```
├── Churn and CLV code.ipynb       # Full notebook including model, insights, and simulations
├── README.md                      # Project documentation
├── /models                        # Optional directory for storing trained models
├── /results                       # Charts, plots, and evaluation metrics
```

## Tools and Technologies

- Python 3
- Jupyter Notebook
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn
- Pandas / NumPy

## Key Deliverables

- Predictive churn model tuned and evaluated on test data
- Summary of top churn drivers and visual explanation
- Designed incentives and estimated their impact
- Recommendations on personalized incentive targeting trhough experiments
- CLV-based financial evaluation of proposed actions


