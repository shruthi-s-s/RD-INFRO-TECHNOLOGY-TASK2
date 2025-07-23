# RD-INFRO-TECHNOLOGY-TASK2
Data Analysis Internship Task 2
# Customer Churn Prediction – Task 2: Exploratory Data Analysis (EDA)

This repository contains the notebook for **Task 2: Exploratory Data Analysis**, part of the Customer Churn Prediction project during an internship at **RD INFRO TECHNOLOGY**.

---

##  Dataset

The dataset used is the cleaned version of `netservicechurnuse.csv`, named `netservicechurnuse_cleaned.csv`. It contains information about:
- Customer subscriptions (TV, movie package, internet)
- Service usage
- Churn status (0 = stayed, 1 = churned)

---

## Task Objectives

In this task, we aimed to explore the dataset and uncover patterns related to customer churn by:
- Visualizing churn distribution using count plots and pie charts
- Comparing churn rates based on:
  - TV subscription status
  - Movie package subscription status
  - Monthly billing
  - Upload/download averages
  - Remaining contract period
- Observing trends to identify which services or behaviors relate to higher churn

We used `seaborn` and `matplotlib` for all visualizations.

---

## Key Visuals & Insights

- **Churn Count**: Bar chart displaying the number of customers who churned vs stayed.
- **Churn Rate**: Pie chart showing percentage distribution between churned and retained customers.
- **TV Subscription vs Churn**: Churn was higher among **non-TV subscribers**.
- **Movie Package vs Churn**: Higher churn rate observed among those **without a movie package**.
- **Billing & Usage Analysis**: Visual patterns indicate churn correlates with billing amount and upload/download usage.

---

## Requirements

Install the required libraries:

```bash
pip install pandas matplotlib seaborn
