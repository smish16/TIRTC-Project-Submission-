# TIRTC-Project-Submission-
# Healthcare Analytics: Doctor Visits Analysis

An exploratory data analysis (EDA) and visualization project focused on understanding patient visit behaviors, health indicators, and financial/insurance coverage impact using Python.

---

## 📌 Project Overview

This project analyzes patient healthcare utilization data to uncover key drivers behind doctor visit frequency. By examining patient demographics, chronic illnesses, activity reduction, and insurance/welfare support types, the analysis provides actionable insights for healthcare resource allocation and policy optimization.

---

## 📁 Dataset Information

- **File Name:** `1776250375-P2-Healthcare Analytics for Doctor Visits.csv`
- **Key Features Analyzed:**
  - `visits`: Number of doctor visits during the observation period.
  - `gender`: Patient gender (`male` / `female`).
  - `illness`: Number of acute illnesses reported.
  - `reduced`: Days of reduced activity due to illness or injury.
  - `lchronic`: Presence of a long-term chronic condition (`yes` / `no`).
  - `private`: Private health insurance coverage status.
  - `freepoor`: Free government healthcare coverage due to low income.
  - `freerepat`: Free government healthcare coverage due to repatriation/veteran status.

---

## 🚀 Key Insights & Findings

1. **Zero-Visit Skewness:** A vast majority of patients (~80%+) had **0 doctor visits** during the period, highlighting a heavily zero-inflated distribution.
2. **Chronic Condition Impact:** Patients with long-term chronic conditions (`lchronic == 'yes'`) visit doctors at a significantly higher average rate compared to those without.
3. **Government Support Dynamics:** Repatriation health coverage recipients (`freerepat`) exhibit notably higher visit frequencies, suggesting higher healthcare needs or lower financial barriers to care.

---

## 🛠️ Tech Stack & Libraries

- **Language:** Python 3.x
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`, `seaborn`

---

## ⚙️ Installation & Usage

1. **Clone or download the repository:**
   ```bash
   git clone [https://github.com/your-username/healthcare-analytics-doctor-visits.git](https://github.com/your-username/healthcare-analytics-doctor-visits.git)
   cd healthcare-analytics-doctor-visits
