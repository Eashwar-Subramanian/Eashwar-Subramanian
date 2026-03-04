# Eashwar Subramanian

Junior Data Analyst / Analytics (Melbourne) — SQL • Python • Power BI • MySQL • Dashboards • Data QA

**Links:** Portfolio · LinkedIn · Resume · Email

---

## Featured work

### Australian Retail Customer Segmentation (Python + Power BI)
I segmented customers from a 5,000-row Australian retail dataset into actionable groups and built an interactive Power BI dashboard.

**Results (reproducible from the repo’s `powerbi_enriched_data.csv`):**
- Customers: **788**
- Total revenue: **$715,541.58**
- Avg revenue per customer: **$908.05**
- Clusters: **3** (414 / 106 / 268 customers)
- Revenue share by cluster: **55.54% / 15.89% / 28.57%**
- Data quality fix: **1,041 / 1,435** order numbers were inconsistent (**72.54%**). I rebuilt stable `transaction_id` logic to preserve cart-level integrity.

Repo: https://github.com/Eashwar-Subramanian/retail-customer-segmentation-australia

---

### Sales Analytics Dashboard (Power BI + MySQL)
A Power BI dashboard built on a MySQL database dump (included in the repo). This repo is set up so a reviewer can restore the DB and connect Power BI to reproduce the model.

Repo: https://github.com/Eashwar-Subramanian/sales-analytics-dashboard-powerbi

---

### Australian Climate Forecast Dashboard (Flask + SARIMAX + Folium)
A Flask web dashboard that:
- lets users select an Australian location,
- generates an on-demand SARIMAX forecast chart,
- shows MAE/RMSE validation when there is enough history,
- embeds a temporal Folium map.

Repo: https://github.com/Eashwar-Subramanian/climate-policy-forecasting-dashboard

---

### SQL projects (MySQL)
- Nashville housing data cleaning in MySQL (standardization, parsing, de-duplication):  
  https://github.com/Eashwar-Subramanian/real-estate-data-cleaning-mysql
- COVID-19 exploration queries + Tableau prep outputs:  
  https://github.com/Eashwar-Subramanian/covid-data-analysis-sql-tableau

---

### Cloud-based Music Subscription App (Java + AWS)
Full-stack coursework project using Java servlets with AWS components (S3, DynamoDB, Lambda, EC2). Includes separate Java programs for S3 bucket creation and automated image download + upload to S3.

Repo: https://github.com/Eashwar-Subramanian/cloud-music-subscription-app

---

## Healthcare RAG evaluation (sanitized; code not public)
I worked on a hospital-scoped RAG system with guardrails and repeatable evaluation. I am sharing a sanitized case study (docs + metrics only; no NDA code).

Sanitized repo (create this): https://github.com/Eashwar-Subramanian/healthcare-rag-evaluation-sanitized

---

## Code review / guidance requests
I want external reviews on:
- README clarity (business framing + reproducibility)
- SQL query structure and readability in the MySQL repos
- Power BI model clarity (tables/measures naming + layout)
- Pipeline reliability patterns (logging, dedupe, outputs)

Open an Issue titled: **Review: <repo-name>** and write blunt feedback. I read every issue.

---

## Tech used in public repos
**Python:** pandas, numpy, scikit-learn, Flask, FastAPI, pytest  
**SQL:** MySQL  
**BI:** Power BI  
**Cloud (coursework repo):** AWS S3, DynamoDB, Lambda, EC2  
**Other:** Git, Docker (local dev patterns)

---

## Learning (not counted as project experience)
Advanced SQL (window functions, performance patterns) + Tableau dashboard design best practices

---

## Education
Master of Data Science — RMIT University (Dec 2025)  
Bachelor of Electronics & Communication Engineering — First Class Distinction
