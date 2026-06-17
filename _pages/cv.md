---
layout: archive
title: "Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Huda Ahmed, M.S.
======

Madison, WI | [hahmed22@wisc.edu](mailto:hahmed22@wisc.edu) | [LinkedIn](https://www.linkedin.com/in/hudaahmedd/) | [GitHub](https://github.com/hudxhl)

Research Profile
======

Master’s-level quantitative health researcher and data scientist with training in psychology, behavioral health research, human subjects research, and applied machine learning. Experienced in behavioral health data collection, ecological momentary assessment (EMA), REDCap and Qualtrics workflows, IRB/protocol development, clinical research coordination, and reproducible statistical analysis using R, Python, SQL, and Quarto.

My work focuses on applying machine learning, statistical modeling, and reproducible analytics to clinical, public health, and human behavior data. I am especially interested in suicide and self-injury research, remote monitoring, wearable and sensor-based methods, patient-centered outcomes, health equity, and data-driven approaches to behavioral health care.

Education
======

**Master of Science in Data Science in Human Behavior**  
University of Wisconsin - Madison, Department of Psychology  
Sep 2024 - Dec 2025  
Specialization in statistical analysis, experimental design, machine learning, and behavioral data science. GPA: 3.7/4.0.

**Bachelor of Science in Psychology**  
University of Minnesota - Twin Cities, Department of Psychology  
Sep 2020 - Aug 2023  
Honors: President’s Student Leadership and Service Award; Dean’s List; Culture Corps Award; Global Excellence Scholarship.

Research Experience
======

**Research Fellow / Graduate Research Assistant**  
Affect, Suicide, Self-Injury, and Social Triggers (ASSIST) Lab, University of Wisconsin–Madison  
Madison, WI | Sep 2024 – Present

* Developed reproducible research data workflows for suicide and self-injury studies, including EMA and survey data collection systems, participant tracking, data documentation, and quality-control procedures.
* Designed and implemented REDCap and Qualtrics instruments with branching logic, longitudinal structures, automated survey workflows, and follow-up assessments for EMA-based behavioral health studies.
* Developed NIH R01 IRB/protocol materials for a longitudinal adolescent NSSI-to-suicidal-behavior study using EMA, computer vision, and technology-enhanced data collection methods.
* Submitted IRB applications and responded to reviewer comments in ARROW, supporting regulatory review processes for suicide and self-injury research protocols.
* Managed participant recruitment, eligibility screening, scheduling, and study tracking across multiple suicide and self-injury research projects using online recruitment platforms and structured tracking systems.
* Conducted informed consent procedures, study sessions, EMA smartphone configuration, and participant-facing study support for longitudinal behavioral health research.
* Administered validated clinical assessments including UWRAP, SITBI, and C-SSRS, and implemented safety planning procedures for participants reporting suicidal ideation or nonsuicidal self-injury.
* Co-authored and maintained study procedural manuals and data documentation to improve consistency in protocol implementation, staff training, participant safety procedures, and research data management.
* Co-authored a systematic review on intensive time sampling methods in suicide research, synthesizing literature on real-time measurement approaches to suicidal thoughts and behaviors.

**Selected studies:** Factors Altering Daily Self-Injury (FADS), Healthy Minds Program App Pilot (HMP), Computerized Adaptive Test for Suicide Risk Pathways (CAT-SRP), Individualized Time Emotion Measurement (ITEM), A Mechanistic Analysis of the Transition from Nonsuicidal to Suicidal Self-Injury in Adolescents (NSSI-SA), and the Suicide Psychoeducation Web Course.

**Research Professional I**  
Minnesota Alcohol and Pain Lab (MAPL), University of Minnesota Medical School  
Minneapolis, MN | Jun 2023 – Jun 2024

* Supported NIH-funded alcohol, pain, wearable sensor, and neuroimaging studies through IRB/protocol preparation, R01 materials, regulatory revisions, continuing reviews, and clinical research operations.
* Consented and screened human subjects research participants, determined study eligibility, scheduled study visits, and managed participant payments.
* Administered REDCap questionnaires, drug and pregnancy tests, breath alcohol concentration assessments, alcohol dosing procedures, and wearable biosensor data collection.
* Collected, cleaned, quality-checked, and managed multimodal research data including REDCap questionnaires, breath alcohol concentration, transdermal alcohol biosensor data, smartwatch sensor outputs, and PHI-containing study records on secure platforms.
* Used RStudio to visualize and manually code accelerometer and gyroscopic smartwatch data as sip intervals for alcohol-use detection research.
* Completed 3T MRI operator training.

**Selected studies:** Automatic Alcohol Use Detection (AAUD), Neural Correlates of Pain and Alcohol Analgesia in Patients with Chronic TMD, and Driven to Discover (D2D): Bottom’s Up!

Selected Data Science Projects
======

**[Machine Learning Prediction of Recent Nonsuicidal Self-Injury](/talks/2026-04-16-nssi-prediction-capstone)**  
R, tidymodels, Quarto, random forest, KNN, glmnet

* Built a reproducible supervised machine learning pipeline to predict recent nonsuicidal self-injury from 100+ behavioral health predictors.
* Engineered a binary NSSI recency outcome, cleaned and recoded predictors, evaluated missingness, and prepared training, validation, and test datasets for model development.
* Compared KNN, random forest, and regularized logistic regression models to evaluate predictive performance and identify behavioral, clinical, and demographic predictors relevant to self-injury risk screening.
* Because this project used sensitive behavioral health data containing protected health information, the underlying dataset and project code cannot be shared publicly. The project summary describes the analytical workflow, modeling approach, evaluation strategy, findings, and future directions while maintaining participant privacy and data security.

**[Machine Learning Prediction of Airline Passenger Satisfaction](/portfolio/airline-passenger-satisfaction/)**  
R, tidymodels, KNN, random forest, ROC/AUC, Quarto

* Built a reproducible supervised classification workflow to predict airline passenger satisfaction from customer experience, service-rating, and flight-delay data.
* Cleaned and prepared a 600-person dataset with approximately 20 predictors, evaluated missingness, reclassed variables, addressed class imbalance, and compared KNN and random forest model configurations.
* Evaluated model performance using ROC/AUC and documented preprocessing, tuning, and final model selection in a reproducible Quarto report for a stakeholder-facing audience.

**[Language Access and Substance Use Treatment Admissions](/portfolio/language-access-regression/)**  
R, linear regression, Type III ANOVA, Quarto

* Modeled whether language-specific treatment services predicted substance use treatment admissions across Midwestern facilities.
* Cleaned and recoded 2023 National Substance Use and Mental Health Services Survey facility-level data, filtering to Midwestern states and preparing predictors for non-English language services, sign-language services, provider type, and state location.
* Fit and interpreted a multiple linear regression model with Type III ANOVA tests, producing a manuscript-style Quarto report that translated statistical findings into implications for treatment access and service availability.

**[SES, Subjective Social Status, and Mental Health Outcomes](/portfolio/mediation-reproduction/)**  
R, lavaan, mediation analysis, Quarto

* Reproduced mediation models testing whether subjective social status explained the relationship between socioeconomic status and depressive symptoms, suicidal ideation, and suicide attempts.
* Cleaned and prepared Add Health Wave IV data, created SES and depression composite measures, recoded suicidality outcomes, and implemented bootstrapped mediation models in lavaan.
* Compared results to the original study, identifying consistent mediation findings for depressive symptoms and suicidal ideation while evaluating methodological reasons for divergent suicide-attempt findings.

Research & Data Skills
======

**Quantitative Methods:** regression, classification, mediation/moderation, linear mixed-effects models, PCA, ROC/AUC, feature importance, cross-validation, missingness checks, reproducible analysis.

**Programming & Reproducible Workflows:** R, tidyverse, tidymodels, ggplot2, Python, SQL, Quarto/R Markdown, Jupyter Notebooks, GitHub.

**Research Systems:** REDCap, Qualtrics, EMA data workflows, longitudinal survey design, ARROW, Ethos, OnCore, Box, Excel tracking systems, data dictionaries, codebooks, WordPress.

**Human Subjects & Clinical Research:** IRB protocol materials, informed consent, participant screening, clinical assessments, safety planning, PHI handling, participant tracking, study documentation.

Publications
======

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Talks and Presentations
======

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

Service and Leadership
======

* President’s Student Leadership and Service Award, University of Minnesota–Twin Cities.
* Culture Corps Award, University of Minnesota–Twin Cities.
* Dean’s List, University of Minnesota–Twin Cities.
* Global Excellence Scholarship, University of Minnesota–Twin Cities.
