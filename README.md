# Phase-3-project-
# Final phase 03 Project Submission

* Student name: Ingavi Kilavuka
* Student pace: full time
* Dataset: SyriaTel Customer Churn
* Instructor name: Mwikali 
# Executive summary
The project's objective is to utilize data analytics and machine learning methods to improve customer experiences and decrease churn for Syriatel, a top mobile network provider in Syria. In the competitive telecommunications sector, retaining current customers and ensuring their satisfaction are crucial for Syriatel's long-term success and growth. The goals of this project include:
- Determining whether customers are indeed leaving
- How can we best predict the amount of customers leaving
- How can this data assist Syriatel improve customer satisfaction 
## Table of contents 
1. [Business Understanding](#1-business-understanding)
    1. [About Syriatel](#11-about-syriatel)
    1. [Stakeholders](#12-stakeholders)
    1. [Business Problem](#13-business-problem)
    1. [Objectives](#14-objectives)
2. [Data Understanding](#2-data-understanding)
    1. [Data Cleaning](#21-data-cleaning)
3. [EDA](#3-eda)
    1. [Univariate analysis](#31-univariate-analysis)
    2. [Bivariate analysis](#32-bivariate-analysis)
    3. [Encoding](#33-encoding)
                    (1.[Label Encoder](#331-label-encoding))
                    (2.[One-Hot Encoder](#332-one-hot-encoding))
4. [Modeling](#4-modeling)
    1. [Logistic Regression](#41-logistic-regression)
    2. [Decision Tree](#42-decision-tree)
    3. [Random Forest](#43-random-forest)
    4. [KNN](#44-k-nearest-neighbors)
    5. [Roc Curve](#45-roc-curve)
    6. [Feature Importances](#46-feature-importance-all-features)
5. [Evaluation & Recommendations](#5-evaluation--recommendations)
    1. [Churn Preditions](#51-churn-prediction)
    2. [Churn Mitigation](#52-churn-mitigation)
    3. [Other Recommendations](#53-other-recommendations)
    # 1. Business understanding
    ## 1.1 About Syriatel
Syriatel (Arabic: سيريتل) is a leading mobile network provider in Syria, established in January 2000 with its headquarters in Damascus. It is one of the only two mobile service providers in the country, alongside MTN Syria. In 2022, Wafa Telecom was awarded the third telecom license by the Syrian telecommunications authority. Syriatel offers LTE services under the brand name Super Surf, providing speeds up to 150 Mb/s.

Initially, Syriatel operated under a Build-Own-Transfer (BOT) contract for 15 years, with management provided by Orascom. In 2017, the company introduced 4G services. On June 5, 2020, a Syrian court placed Syriatel under judicial custody.
## 1.2 Stakeholders
- **Customers:** Existing customers are directly affected by the company's efforts to reduce churn, which often lead to improved services, better customer support, and enhanced loyalty programs. Customers who experience better service are less likely to leave
- **Management:** Responsible for strategic decision-making, they are directly impacted by customer churn as it affects the company's revenue, profitability, and market position. High churn rates can indicate issues with customer satisfaction or service quality, prompting them to implement corrective measures 
- **Employees:** Job security and career growth for employees can be affected by churn. If high churn rates lead to financial losses, it might result in cost-cutting measures, including layoffs or reduced resources for employee development
