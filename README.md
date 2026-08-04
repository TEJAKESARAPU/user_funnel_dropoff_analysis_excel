# 📊 App User Funnel Analysis using Excel & Python

An end-to-end user funnel analysis project built using **Microsoft Excel** and **Python** to analyze user progression through a website/app signup funnel. The project measures stage-wise conversion rates, identifies user drop-offs, and presents actionable insights through an interactive dashboard.

---

## 📌 Project Overview

Understanding where users abandon a signup or purchase journey is essential for improving product performance. This project analyzes event-level funnel data to measure user progression across each stage, identify bottlenecks, and provide recommendations to improve conversion rates.

---

## 🎯 Objectives

- Count unique users at each funnel stage.
- Calculate stage-wise conversion rates.
- Identify the biggest user drop-off.
- Analyze overall funnel performance.
- Create an interactive dashboard for business stakeholders.

---

## 🛠️ Tech Stack

- **Microsoft Excel**
  - Pivot Tables
  - Pivot Charts
  - Funnel Chart
  - Excel Formulas
  - Conditional Formatting
  - Dashboard Design
- **Python**
  - Pandas
  - Jupyter Notebook

---

## 📂 Repository Structure

```text
user_funnel_dropoff_analysis_excel/
│
├── data/
│   └── funnel_events_sample.csv
│
├── funnel_dropoff_analysis.xlsx
├── funnel_dropoff_analysis.ipynb
├── dashboard.png
└── README.md
```

---

## 📊 Dataset

The dataset contains event-level user interactions with the following fields:

| Column | Description |
|---------|-------------|
| `user_id` | Unique identifier for each user |
| `step` | Funnel stage reached by the user |
| `timestamp` | Date and time of the event |

### Funnel Stages

1. Visited Site
2. Signup Started
3. Details Filled
4. Email Verified
5. Purchase Completed

---

## 📈 Analysis Performed

### Data Quality Checks
- Verified missing values
- Checked for duplicate records
- Validated data types
- Confirmed correct funnel sequence

### Funnel Analysis
- Counted unique users at each stage
- Calculated stage-wise conversion rates
- Calculated stage-wise drop-off percentages
- Identified the biggest funnel bottleneck

### Dashboard
The interactive dashboard includes:

- KPI Cards
- Funnel Chart
- Stage Conversion Rate
- Stage-wise User Drop-off
- User Segment Comparison
- Data Quality Check
- Business Insights

---

## 📌 Key Metrics

| Metric | Value |
|---------|------:|
| Total Users | 200 |
| Completed Purchases | 44 |
| Overall Conversion | 22.00% |
| Biggest Drop-off | 45.83% |

---

## 💡 Key Insights

- A total of **200 users** entered the application funnel.
- **150 users (75%)** progressed from **Visited Site** to **Signup Started**.
- The **Details Filled → Email Verified** stage recorded the highest drop-off (**45.83%**), making it the primary bottleneck in the funnel.
- After email verification, **84.62%** of users completed the purchase, indicating a smooth final conversion stage.
- Only **44 users** completed the entire funnel, resulting in an overall conversion rate of **22%**.

---

## ✅ Recommendations

- Simplify the email verification process.
- Implement one-click email verification.
- Send reminder emails to users who have not verified their accounts.
- Monitor email verification failures to reduce user abandonment.
- Continuously track funnel performance to improve conversion rates.

---

## 📷 Dashboard Preview

![Dashboard](dashboard1.png)

---

## 🚀 Files Included

| File | Description |
|------|-------------|
| `funnel_dropoff_analysis.xlsx` | Excel dashboard with analysis and visualizations |
| `funnel_dropoff_analysis.ipynb` | Python notebook for funnel analysis |
| `dashboard.png` | Dashboard preview |
| `data/funnel_events_sample.csv` | Sample dataset used for analysis |

---

## 📚 Skills Demonstrated

- Data Analysis
- Funnel Analysis
- Product Analytics
- KPI Reporting
- Microsoft Excel
- Python (Pandas, Matplotlib)
- Dashboard Design
- Data Visualization
- Business Insights

---

## ⭐ Project Outcome

This project demonstrates how Excel and Python can be combined to analyze user behavior, measure conversion performance, identify funnel bottlenecks, and build business-ready dashboards that support data-driven decision-making.
