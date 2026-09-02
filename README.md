# Online Retail II — Cancellation Loss Analysis

## Project Overview

This project investigates how product cancellations impact an e-commerce business using the **Online Retail II** dataset from the UCI Machine Learning Repository.

Instead of measuring returns through a single KPI, I analyzed cancellation loss from four business perspectives:

* 🌍 Geographic Analysis
* 📅 Temporal Analysis
* 👥 Customer Risk Analysis
* 📦 Product Risk Analysis

The goal was to identify where revenue leakage occurs and recommend targeted business actions.

## Business Problem

Returns have become a major operational cost for retailers.

Using over **1 million transactions**, this project identified approximately **£1.29 million** in cancellation losses across two years, with the UK representing the largest financial exposure while Germany and EIRE showed significantly higher cancellation rates.

## Dataset

* **Source:** UCI Machine Learning Repository
* **Period:** December 2009 – December 2011
* **Rows:** 1,048,576
* **Countries:** 43

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* SciPy
* Jupyter Notebook

## Analytical Methods

### Geographic Analysis

* Country-level aggregation
* Cancellation rate calculation
* Chi-square significance testing

### Temporal Analysis

* Monthly trends
* Quarterly trends
* Year-over-year comparison

### Customer Analysis

* Pareto (80/20) Analysis
* RFMR Segmentation
* Spearman Rank Correlation

### Product Analysis

* SKU-level Pareto Analysis
* Price-band segmentation
* Invoice drill-down investigation

## Key Findings

### 1. UK drives financial exposure

* **85% of cancellation loss** originated from the UK.
* Germany and EIRE experienced much higher cancellation rates despite lower sales volume.

### 2. Returns spike during Q4

* Q4 generated the largest cancellation losses.
* The cancellation rate remained relatively stable, indicating higher order volume—not changing customer behavior.

### 3. Customer behavior matters

* Frequent buyers cancelled significantly less.
* Spearman correlation showed a strong negative relationship between purchase frequency and return rate.

### 4. Product insights

* A single wholesale cancellation created the largest SKU loss.
* Higher-priced products showed much higher return rates than low-priced products.

## Business Recommendations

Instead of applying one blanket return policy, the analysis recommends three intervention strategies:

* **Control:** Reduce one-off bulk order risk.
* **Investigate:** Review products and fulfillment causing recurring cancellations.
* **Retain:** Protect valuable customers with proactive engagement.

## Repository Contents

* Full Jupyter Notebook
* Business Report
* Presentation
* Visualizations

## Author

**Sandra Raj Pattuvakkaran**

M.Sc. Data Science | Data Analyst | Business Analytics
