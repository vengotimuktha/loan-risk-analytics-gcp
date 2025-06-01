# Loan Risk Analytics with Google Cloud  
**BigQuery SQL + Looker Studio | End-to-End Cloud Data Analysis Project**

## Overview
This project was completed as part of the **Google Cloud Data Analytics Certificate**, simulating a real-world role as a **Cloud Data Analyst at TheLook Fintech**, a growing financial technology company.

The goal was to help the Treasury department track cash flow, understand borrower behavior, and assess geographic loan distribution using Google Cloud’s BigQuery and Looker Studio.

---

## Project Objectives

The project was divided into two cloud-based labs:

###  Part 1: BigQuery-Based Data Analysis  
Performed exploratory data analysis and reporting in BigQuery to answer:

1. **Cash Flow Monitoring**  
   - Compared loan funding vs. payments received  
   - Identified daily and yearly loan issuance trends  

2. **Loan Purpose Analysis**  
   - Found top reasons for taking out loans  
   - Cleaned and deduplicated loan purpose data

3. **Geographic Risk Distribution**  
   - Tracked borrower locations across states  
   - Joined regional mapping data to enrich state-level analysis

#### Key Tasks:
- Created SQL queries to transform, filter, and aggregate loan data
- Imported external data to classify regions
- Created summary tables for daily and yearly loan metrics
- Removed duplicates to ensure clean visual reporting

---

###  Part 2: Looker Studio Dashboard Design  
Built an executive-level dashboard in Looker to support Treasury KPIs:

#### Key Business Questions Answered:
1. What is the **total outstanding loan amount**?
2. What **percentage of loans** fall under each status category (e.g., Current, Late, Default)?
3. Which **states have the most loans** issued?
4. Which **customers own homes** outright and have “Current” loans?

#### Dashboard Features:
- Pie chart: Outstanding loans by status
- KPI card: Total loan balance
- Bar chart: Top 10 states by loan count
- Table: Homeowners with active loans
- Enabled **cross-filtering** and **auto-refresh** for interactivity

>  [View Sample Dashboard Screenshot](Looker_Dashboard_Image.png)

---

## Tools & Technologies

| Tool             | Usage                                 |
|------------------|----------------------------------------|
| **BigQuery**     | SQL-based data analysis and joins      |
| **Cloud Storage**| External data ingestion                |
| **Looker Studio**| Interactive dashboard creation         |
| **Qwiklabs**     | Temporary GCP access for lab execution |

---

## Business Impact

This project demonstrated the ability to:
- **Collect, clean, and store data** for analysis
- **Perform complex joins and aggregations**
- **Design KPI-driven dashboards** for decision-making
- **Align data insights with real business needs** in fintech

---

## Limitations

- The project was executed on temporary credentials via Qwiklabs
- Source code and queries were not preserved after session expiration
- Dashboard is not publicly accessible due to access constraints

---

## Certificate

This project was completed under the official [Google Cloud Data Analytics Certificate](google_cloud_data_analytics_certificate.png).

---

## About the Author

**Mukthasree Vengoti**  
Google Cloud Data Analyst | Google Cloud Certified  
[LinkedIn](https://www.linkedin.com/in/mukthasree-vengoti/)
