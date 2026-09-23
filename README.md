# Telco-customer-churn-dashboard
Uncovering telecom customer churn drivers through Python data processing and an executive Power BI dashboard.

# 📊 Telecom Customer Churn Analysis & Retention Dashboard

An end-to-end business intelligence solution built in **Power BI** designed to analyze customer churn behavior, identify high-risk demographic and product segments, and deliver strategic, data-driven retention recommendations for executive leadership.

---

## 📌 Project Overview
Customer churn is one of the most critical challenges in the telecommunications industry. This project utilizes the **IBM Telco churn dataset (sourced from Kaggle)** to diagnose the root causes of customer attrition. The resulting interactive, 4-page Power BI dashboard bridges the gap between raw data and actionable business strategy, targeting a reduction in early-tenure and month-to-month churn.

---

## 🛠️ Tools & Technologies Used
* **Python:** Data extraction, inspection, and initial cleaning.
* **Power BI & Power Query:** Data transformation, data modeling, interactive filtering, and dashboard design.
* **DAX (Data Analysis Expressions):** Creating custom measures (e.g., Churn Rate %, average financial metrics).

---

## 🧹 Data Cleaning & Transformation
Before importing into Power BI, the dataset was cleaned using **Python** to handle initial formatting and missing values. Final shaping, relationship modeling, and optimization were handled via **Power Query** to ensure repeatable and clean transformations:
* Imported the raw Kaggle telecom dataset and addressed missing/null values in columns like total charges.
* Standardized data types across numeric fields and categorical demographic columns.
* Structured tables and created custom conditional columns to optimize dashboard filtering and performance.

---

## 📑 Dashboard Structure & Architecture

The report is structured into four logical pages, guiding stakeholders from a macro-level overview down to granular tactical actions:

1. **Executive Overview (Page 1):** 
   - High-level KPI cards tracking **Total Customers** and overall **Churn Rate %**.
   - Global slicers allowing cross-filtering across the entire report.

     Executive Summary
     <img width="1202" height="677" alt="Screenshot 2026-09-22 225010" src="https://github.com/user-attachments/assets/e3a51deb-8e3e-4325-bda0-3f8bdc233f58" />

2. **Customer Demographics & Profiles (Page 2):** 
   - Explores personal attributes including senior status, partners, and dependents.
   - Highlights how family structures impact customer retention and loyalty.

     Customer Demographics
     <img width="1202" height="675" alt="Screenshot 2026-09-22 225107" src="https://github.com/user-attachments/assets/0cf05f37-e9d0-4d11-afef-ebba8c3bd587" />

3. **Service, Contract & Billing Risk Analysis (Page 3):** 
   - Evaluates operational and financial drivers, isolating contract types (Month-to-Month vs. Long-term), internet service tiers (Fiber Optic vs. DSL), and payment methods.
   - Proves that financial flexibility and lack of commitment are primary root causes of customer loss.

     Contract & Service Analytics
     <img width="1198" height="675" alt="Screenshot 2026-09-22 230257" src="https://github.com/user-attachments/assets/ad911eca-360a-4b96-a751-6915f02e78f8" />

4. **Strategic Recommendations & Retention Action Plan (Page 4):** 
   - Features a tenure lifecycle curve exposing the critical **0–6 month early-tenure churn spike**.
   - Delivers executive-level recommendations (e.g., onboarding touchpoints, contract migration incentives, and automatic bundling of security add-ons).

     Strategic Recommendations & Retention Action
      <img width="1201" height="676" alt="Screenshot 2026-09-22 230414" src="https://github.com/user-attachments/assets/278ed995-061a-4436-8f41-46c5f3f05483" />
---

## 🔑 Key Business Insights

* **The Contract Vulnerability:** Month-to-month contracts experience a disproportionately high churn rate (surpassing 42%), compared to locked-in 1-year and 2-year commitments.
* **The Fiber Optic Paradox:** Despite being a high-tier product, Fiber Optic internet users exhibit severe churn volatility, heavily tied to electronic check billing friction.
* **The Onboarding Drop-off:** The customer lifecycle curve reveals that the vast majority of churn occurs within the first few months, highlighting an urgent need for proactive customer success check-ins.

---

## 📂 Repository Contents
* `Telco_Customer_Churn_Dashboard.pbix` - The complete interactive Power BI source file.
* `telco_churn_cleaned` - The preprocessed dataset cleaned via Python.
  [telco_churn_cleaned.csv](https://github.com/user-attachments/files/32568722/telco_churn_cleaned.csv)

---

## 💡 How to View This Project
1. **Interactive Experience:** Download the `.pbix` file and open it using [Power BI Desktop](https://powerpbifree.com/).

