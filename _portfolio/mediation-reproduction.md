---
title: "Socioeconomic Status, Subjective Social Status, and Mental Health Outcomes"
excerpt: "Reproducible mediation analysis examining whether perceived social standing helps explain links between socioeconomic status and mental health outcomes."
collection: portfolio
permalink: /portfolio/mediation-reproduction/
---

## Project Overview

Reproduced a published mediation analysis to evaluate whether perceived social standing helps explain the relationship between socioeconomic conditions and mental health outcomes. The project focused on depressive symptoms, suicidal ideation, and suicide attempts, using Wave IV data from the National Longitudinal Study of Adolescent to Adult Health.

The goal was to assess whether subjective social status functions as a meaningful pathway between objective socioeconomic indicators and mental health outcomes. From an applied perspective, this project shows how reproducible statistical workflows can be used to validate published findings, identify where results are sensitive to analytic decisions, and communicate uncertainty clearly.

## Why This Project Matters

Mental health outcomes are shaped by both structural conditions and individual perceptions of social position. Understanding these pathways can help organizations, researchers, and public health teams better identify mechanisms of risk and prioritize interventions related to mental health equity.

## Methods

I built a reproducible analysis workflow that included:

- Reconstructing socioeconomic status, subjective social status, depressive symptoms, suicidal ideation, and suicide attempt variables
- Preparing and cleaning Add Health survey data
- Implementing mediation models in R
- Comparing reproduced findings against the original published analysis
- Documenting areas where results converged or diverged

## Key Findings

The reproduction supported the original findings for depressive symptoms and suicidal ideation: subjective social status significantly mediated the relationship between socioeconomic status and both outcomes.

However, the mediation pathway for suicide attempts was not significant in my reproduction, suggesting that this result may be more sensitive to methodological choices such as covariate selection, missing data handling, survey weights, or model specification.

The original study reported that subjective social status explained approximately **27%** of the socioeconomic status-depressive symptoms relationship, **51%** of the socioeconomic status-suicidal ideation relationship, and **37%** of the socioeconomic status-suicide attempt relationship. My reproduction broadly validated the depression and ideation patterns while highlighting uncertainty around the suicide attempt pathway.

## Tools and Skills

**Tools:** R, Quarto, lavaan, GitHub  
**Methods:** Mediation analysis, regression modeling, reproducible reporting, data cleaning, statistical validation  
**Skills demonstrated:** Reproducible analytics, statistical interpretation, research translation, uncertainty communication, mental health data analysis

## Future Directions

Future improvements could include incorporating survey weights, testing additional covariates, evaluating subgroup differences, and translating results into clearer decision-support insights for organizations focused on mental health equity, prevention strategy, and resource allocation.

## Project Links

[View full HTML report](/files/mediation-reproduction.html){: .btn .btn--primary}

[View source code and project files](https://github.com/hudxhl/data-science-portfolio/tree/main/mediation_reproduction){: .btn .btn--info}
