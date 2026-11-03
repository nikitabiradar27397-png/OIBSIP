# Task 2: Customer Segmentation Analysis

## Domain
Data Analytics — Oasis Infobyte SIP

## Project Overview
This project applies unsupervised machine learning techniques to segment an e-commerce customer base based on historical purchasing behavior. Using the RFM (Recency, Frequency, Monetary) framework, customers are grouped into distinct behavioral profiles to enable data-driven, targeted marketing strategies.

## Tech Stack & Libraries
* **Language**: Python 3
* **Libraries**: Pandas, NumPy, Scikit-learn (KMeans, StandardScaler), Matplotlib, Seaborn

## Key Methodology & Findings
1. **Data Preprocessing & RFM Calculation**:
   * Removed canceled transactions and records with missing customer identifiers.
   * Calculated **Recency** (days since last purchase), **Frequency** (total distinct transactions), and **Monetary** (total spend) per customer.
2. **Feature Scaling & Clustering**:
   * Standardized RFM features using `StandardScaler`.
   * Evaluated the optimal number of clusters using the **Elbow Method** (WCSS metric).
   * Grouped customer base into actionable segments: *High-Value Loyalists*, *Occasional Shoppers*, and *At-Risk Inactive Customers*.
3. **Strategic Applications**:
   * Tailored retention, upselling, and win-back strategies mapped to each cluster's spending and frequency profile.

## Deliverables
* `task2_customer_segmentation.ipynb`: Documented Jupyter notebook with data processing, clustering logic, visualizations, and segment profiles.