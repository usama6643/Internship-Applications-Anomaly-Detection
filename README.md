# Internship Applications Anomaly Detection

## Overview
This project identifies anomalies in internship applications to prevent fake entries. Using machine learning techniques such as **Isolation Forest** and **K-Means Clustering**, it detects suspicious patterns like:

- Duplicate emails or entries  
- Rapid submissions from the same IP  
- Inconsistent CGPA or skill count data  

The system generates alerts for suspicious applications and includes visualizations for analysis.

---

## Features
- Data cleaning and preprocessing
- Feature engineering for anomaly detection
- Machine learning models:
  - Isolation Forest
  - K-Means Clustering
- Alerts for suspicious applications
- Visualizations: histograms, scatter plots, cluster view

---

## Dataset
- `data/internship_applications_dataset.csv`  
- Synthetic dataset with 500 entries including anomalies (duplicate emails, rapid submissions, unusual IP activity)

---

## Usage

### 1. Install dependencies
```bash
pip install -r requirements.txt
