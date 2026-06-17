# D2C Customer Churn Capstone - Part 2

## RFM Segmentation & Retention Strategy

### Project Objective

The objective of this project is to identify customer segments using RFM (Recency, Frequency, Monetary) analysis and additional behavioural signals. The segmentation framework helps prioritize retention efforts before deploying machine learning models.

---

## Dataset

The analysis uses the D2C Customer Churn dataset provided as part of the capstone project.

Key data sources include:

* Customers
* Orders
* Support Tickets
* Web Activity Snapshots
* Campaign History

---

## Methodology

### 1. RFM Feature Creation

The following customer-level features were created:

* Recency
* Frequency
* Monetary Value

### 2. Additional Behavioural Signals

The segmentation was enhanced using:

* Support Ticket Count
* Sentiment Score
* Reopened Tickets
* Return Rate
* Discount Usage
* Campaign Engagement
* Web Activity Metrics
* Loyalty Tier

### 3. Customer Segmentation

Customers were grouped into the following segments:

* Champions
* Loyal Customers
* Dormant Customers
* Discount Sensitive Customers
* High Value But Unhappy Customers
* Regular Customers

### 4. Retention Strategy

A customized retention strategy was designed for each customer segment based on customer value, engagement behaviour, and churn risk.

---

## Repository Contents

* `rfm_segmentation.ipynb` – Complete RFM segmentation workflow
* `segments.csv` – Final customer segmentation dataset
* `retention_strategy.md` – Segment-wise retention recommendations
* `manual_review_cases.md` – Manual review of ambiguous customer cases
* `requirements.txt` – Required Python libraries

---

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Outcome

The project provides an interpretable customer segmentation framework that supports targeted retention campaigns, budget prioritization, and future churn prediction initiatives.
