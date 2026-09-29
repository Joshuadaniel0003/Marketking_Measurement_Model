# Marketking_Measurement_Model
Bayesian Marketing Mix Modeling, response curves, ROI analysis, and constrained budget optimization using Google Meridian.

## 📌 Project Overview

This project develops an end-to-end **Marketing Measurement and Marketing Mix Modeling (MMM)** framework to understand how different marketing channels contribute to business outcomes and how a fixed marketing budget can be reallocated to improve the modeled KPI.

The analysis combines:

- Exploratory Data Analysis
- Baseline regression modeling
- Media adstock / carryover analysis
- Saturation analysis
- Bayesian Marketing Mix Modeling
- Model diagnostics and health checks
- Channel contribution analysis
- ROI and marginal ROI
- Response curves
- Budget optimization
- Constraint sensitivity analysis

The primary modeling framework used is **Google Meridian**, a Bayesian MMM framework designed for measuring media effectiveness and supporting budget allocation decisions.

---

## 🎯 Business Problem

Marketing teams need to answer questions such as:

1. How much does each marketing channel contribute to conversions?
2. How does advertising carry over over time?
3. Does increasing spend produce proportional increases in conversions?
4. Which channels have higher marginal returns?
5. How does the effectiveness of a channel change as spending increases?
6. How should a fixed marketing budget be allocated across channels?
7. Are the recommended allocations stable under different business constraints?

This project addresses these questions using a Bayesian MMM framework.

---

## 📊 Dataset

The project uses the **Google Meridian simulated multi-geo marketing dataset**.

### Dataset Structure

| Attribute | Value |
|---|---:|
| Observations | 6,240 |
| Geographies | 40 |
| Weeks | 156 |
| Marketing Channels | 5 |
| Time Period | 2021–2024 |
| Historical Marketing Spend | ~$219.49M |
| KPI | Conversions |

### Marketing Channels

The dataset contains five paid media channels:

- Channel 0
- Channel 1
- Channel 2
- Channel 3
- Channel 4

Each channel contains:

- Impressions
- Spend

### Additional Variables

The model also incorporates:

- Competitor sales control
- Sentiment score control
- Promotional indicator
- Population
- Revenue per conversion

---

# 🔬 Methodology

The project follows the pipeline:

```text
Raw Marketing Data
        ↓
Data Validation & Preparation
        ↓
Exploratory Data Analysis
        ↓
Baseline Regression
        ↓
Adstock / Carryover Analysis
        ↓
Saturation Analysis
        ↓
Bayesian Marketing Mix Model
        ↓
Model Diagnostics
        ↓
Channel Contribution
        ↓
ROI & Marginal ROI
        ↓
Response Curves
        ↓
Budget Optimization
        ↓
Constraint Sensitivity Analysis
        ↓
Business Interpretation
