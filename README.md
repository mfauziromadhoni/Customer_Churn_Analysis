# 📊 Customer Churn Analysis
### Bank Customer Retention Intelligence | Microsoft Excel Portfolio

---

## Overview

This project presents an end-to-end churn analysis of **10,000 bank customers**, built entirely in Microsoft Excel. The goal is to identify at-risk customers, quantify the financial impact of churn, and produce actionable retention strategies — structured as a professional analytical portfolio for the banking industry.

> *From raw data to business recommendation — no code, no shortcuts.*

---

## Dataset

| Attribute | Detail |
|---|---|
| Source | Bank Customer Churn Dataset |
| Records | 10,000 customers |
| Features | 14 variables (demographic, behavioral, financial) |
| Target Variable | `Exited` — whether a customer churned (1) or was retained (0) |
| Overall Churn Rate | **20.4%** |

---

## Project Structure

| Sheet | Description |
|---|---|
| `HOME` | Project overview & navigation hub |
| `RAW_DATA` | Original dataset, untouched |
| `CLEAN_DATA` | Cleaned data + engineered features (AgeGroup, BalanceSegment, RiskLabel) |
| `EDA` | Exploratory analysis — churn breakdown by geography, age, products, activity status |
| `RISK_SCORING` | Rule-based risk scoring model using 6 behavioral & demographic factors |
| `MODEL_VALIDATION` | Confusion matrix, Accuracy, Precision, Recall, F1-Score, threshold sensitivity analysis |
| `BUSINESS_REC` | Executive summary, financial impact estimation, retention strategies, KPI targets |

---

## Key Findings

- 🇩🇪 **Germany** has a churn rate of **32.4%** — twice the rate of France and Spain
- 👤 Customers aged **46–60** represent the highest-churn age group
- 📦 Customers with **3–4 products** churn at **83–100%** — excessive cross-selling backfires
- 💤 **Inactive members** churn at **26.9%** vs. 14.3% for active members
- ⚠️ At threshold ≥6, the scoring model captures **54.87% of churners** with **53.07% precision**

---

## Analytical Approach

### 1 — Exploratory Data Analysis
Profiled churn behavior across all key dimensions using `COUNTIFS`, `AVERAGEIF`, and PivotCharts. Identified the four strongest churn signals in the dataset.

### 2 — Rule-Based Risk Scoring
Assigned weighted risk scores to each customer based on six factors:

| Factor | Weight |
|---|---|
| Inactive member | +3 |
| 3+ products | +3 |
| Age > 45 | +2 |
| Geography = Germany | +2 |
| Gender = Female | +1 |
| Balance = 0 | +1 |

Customers are classified as 🔴 High Risk (≥7), 🟡 Medium Risk (4–6), or 🟢 Low Risk (<4).

### 3 — Model Validation
Evaluated model performance across multiple thresholds (4–9) using a full confusion matrix framework. Threshold ≥6 identified as optimal — balancing Recall and Precision for retention use cases.

### 4 — Business Recommendation
Translated analytical findings into segmented retention strategies with estimated financial impact and measurable KPI targets.

---

## Tools

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)

---

## About

**[Muhammad Fauzi Romadhoni]**
Industrial Electrical Engineering Graduate — Politeknik Elektronika Negeri Surabaya
K3 Umum Certified (BNSP) | Data Analysis Enthusiast

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/mfauziromadhoni/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat&logo=gmail)](mailto:mfauzir2477@gmail.com)

---

*This project was built as part of a data analytics portfolio targeting roles in the banking and financial services industry.*
