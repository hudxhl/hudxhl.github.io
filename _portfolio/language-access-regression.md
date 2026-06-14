---
title: "Language Access and Substance Use Treatment Admissions"
excerpt: "Regression analysis examining whether language-access services predict admissions at substance use treatment facilities."
collection: portfolio
permalink: /portfolio/language-access-regression/
---

## Project Overview

Analyzed whether language-access services predicted substance use treatment admissions across Midwestern treatment facilities using 2023 SAMHSA National Substance Use and Mental Health Services Survey data. The project evaluated whether accessibility-related facility features, including non-English treatment services and sign language services, were associated with higher client admissions.

The goal was to translate a public health accessibility question into an interpretable regression workflow that could support stakeholder-facing insights about service utilization, treatment access, and resource planning.

## Why This Project Matters

Access to treatment is shaped by more than service availability. Language accessibility can influence whether individuals are able to find, understand, and engage with treatment options. For healthcare systems, public agencies, and community organizations, understanding which accessibility features relate to treatment utilization can support better planning and more equitable service delivery.

This project demonstrates how public datasets can be used to evaluate practical questions about healthcare access and facility-level service patterns.

## Methods

I built an interpretable regression workflow that included:

- Subsetting the dataset to Midwestern substance use treatment facilities
- Cleaning and recoding facility-level service variables
- Preparing language-access indicators and state-level predictors
- Modeling total substance use treatment admissions using linear regression
- Interpreting model results in terms of accessibility, utilization, and stakeholder relevance

## Key Findings

The final analytic sample included **2,543 Midwestern facilities**. The overall regression model was statistically significant, **F(14, 2514) = 2.84, p = .0003**, though the model explained a small proportion of variance in admissions, **R² = .016, adjusted R² = .010**.

Among the predictors, **sign language services** significantly predicted higher admissions, **b = 121.36, SE = 56.66, F(1, 2514) = 4.59, p = .032**. Facilities offering sign language services averaged approximately **121 more admissions** than facilities that did not.

General non-English substance use treatment services were not significant, **p = .919**, and type of language-service provider was also not significant, **p = .655**. Facility state did not reach statistical significance as a block, **p = .116**.

## Tools and Skills

**Tools:** R, Quarto, GitHub  
**Methods:** Linear regression, public health data analysis, categorical predictors, model interpretation, data cleaning  
**Skills demonstrated:** Stakeholder-facing analytics, accessibility analysis, regression modeling, public health reporting, reproducible research

## Future Directions

Future improvements could include adding facility size, urban-rural location, insurance and payment options, treatment type, community-level demographics, and local language need indicators. These additional predictors would help clarify whether language-access services are independently associated with treatment utilization or are acting as proxies for broader facility capacity and accessibility.

## Project Links

[View full HTML report](/files/language-access-regression.html){: .btn .btn--primary}

[View source code and project files](https://github.com/hudxhl/data-science-portfolio/tree/main/reproducible_regression){: .btn .btn--info}
