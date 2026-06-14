---
title: "Predicting Airline Passenger Satisfaction"
excerpt: "Machine learning project predicting airline passenger satisfaction from customer, flight, and service-experience data."
collection: portfolio
permalink: /portfolio/airline-passenger-satisfaction/
---

## Project Overview

Built a machine learning workflow to predict airline passenger satisfaction from customer, flight, and service-experience data, achieving a test-set auROC of **0.9472**. The project used classification modeling to identify patterns in customer satisfaction and translate passenger survey data into practical customer experience insights.

The dataset included **600 airline passenger survey responses** and approximately **20 predictors**, including customer demographics, service ratings, and flight delay variables. The outcome was imbalanced, with **400 satisfied** passengers and **200 neutral or dissatisfied** passengers, so model performance was evaluated using auROC rather than relying only on accuracy.

## Why This Project Matters

Customer satisfaction is a key business outcome for service-based industries. This project shows how customer survey data can be transformed into predictive insights that help identify which parts of the passenger experience may be most important for satisfaction, retention, and service improvement.

Rather than only describing satisfaction trends, this analysis used machine learning to predict satisfaction status and evaluate how well the model generalized to unseen data.

## Methods

I built an end-to-end classification workflow that included:

- Cleaning and preparing passenger survey data
- Handling missing values
- Splitting the data into training and test sets
- Comparing K-nearest neighbors and random forest models
- Evaluating model performance using auROC
- Interpreting model results in the context of customer experience strategy

## Key Findings

The random forest model outperformed the K-nearest neighbors workflow and generalized well to the held-out test set.

**Key metric:** Test-set auROC = **0.9472**

This indicates strong model performance in distinguishing satisfied passengers from neutral or dissatisfied passengers. The results suggest that passenger experience variables can provide meaningful signal for predicting satisfaction and identifying potential areas for service improvement.

## Tools and Skills

**Tools:** R, Quarto, tidymodels, GitHub  
**Methods:** Classification modeling, random forest, K-nearest neighbors, train-test splitting, feature engineering, model evaluation  
**Skills demonstrated:** Machine learning workflow development, customer analytics, predictive modeling, reproducible reporting

## Future Directions

Future improvements could include tuning classification thresholds based on business costs, improving model performance for neutral or dissatisfied passengers, testing additional algorithms, and building an interactive dashboard to monitor satisfaction drivers over time.

## Project Links

[View full HTML report](/files/airline-satisfaction-prediction.html){: .btn .btn--primary}

[View source code and data](https://github.com/hudxhl/data-science-portfolio/tree/main/ml_prediction){: .btn .btn--info}
