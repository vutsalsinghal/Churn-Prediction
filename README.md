# Churn Prediction (Kaggle)

## Description
Customer churn, also known as customer attrition, occurs when customers stop doing business with a company. The companies are interested in identifying segments of these customers because the price for acquiring a new customer is usually higher than retaining the old one. 

For example, if Netflix knew a segment of customers who were at risk of churning they could proactively engage them with special offers instead of simply losing them.

## Objective

- Given a training set of past churn data, your goal in this homework is to predict whether a person will leave the network (churn) or stay.
- [Note] Packages to be used: Numpy, Pandas, SciPy, scikit-learn

## Data description

- Each row represents a customer of the network, with the parameters for each customer described below.
- The data consists of 20,000 customers, split into 90% (18,000) for training data and the remaining 10% (2,000) as test data (holdout).
- You can find the labeled training data in `data/train.csv` and unlabeled test data in `data/test.csv`.

| Columns | Description|
|---|---|
|COLLEGE| Is the customer college educated?|
|INCOME| Annual income|
| OVERAGE| Average overcharges per month|
|LEFTOVER | Average number of leftover minutes per month
|HOUSE |  Estimated value of dwelling (from census tract) |
| HANDSET_PRICE | Cost of phone |
| OVER_15MINS_CALLS_PER_MONTH | per month Average number of long calls (15 mins or over)|
|AVERAGE_CALL_DURATION | Average duration of a call |
|REPORTED_SATISFACTION | Reported level of satisfaction |
|REPORTED_USAGE_LEVEL | Self-reported usage level|
|CONSIDERING_CHANGE_OF_PLAN | Whether the customer considered changing their plan |
|LEAVE (Target variable) | Did the customer stay or leave (churn)? |