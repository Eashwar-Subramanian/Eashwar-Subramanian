# Eashwar Subramanian — Analytics / Data Science (Melbourne)

I build **business-facing analytics** (SQL/Python/Power BI) and **production-style data systems** (APIs, evaluation, pipelines).  
Right now I’m targeting **Junior / Associate** roles in **Insights / BI / Analytics / Data**.

**Links:** Portfolio • LinkedIn • Resume • Email  
> (Tip: keep links here only — remove phone number from GitHub)

---

## Start here (2 minutes)

### 1) Australian Retail Customer Segmentation (Python + Power BI)
**Goal:** turn messy retail transactions into actionable customer segments.  
**Proof artifacts:** notebook + cleaned datasets + PBIX dashboard.

- Segmented **788 customers** into **3 clusters** using **RFM + K-Means**
- Total customer revenue in dashboard dataset: **$715.54K**
- Highest-value cluster: **106 customers contributing ~15.9%** of revenue
- Data quality fix: detected **1,041 / 1,435 (72.54%) inconsistent order_no** values and rebuilt stable `transaction_id`

➡️ Repo: `retail-customer-segmentation-australia`  
➡️ If you only open one file: **Power BI dashboard (.pbix)**

---

### 2) Solara DS — Hospital-scoped RAG (sanitized)
**Goal:** retrieval-augmented QA with safety constraints + evaluation.

**Proof artifacts:** evaluation report + chunking comparison + tests + API.
- RAGAS evaluation: **50 queries**, **38 valid responses** (**12 blocked by guardrails**)
- Retrieval quality (RAGAS): **Context Precision 92.7%**, **Context Recall 91.2%**
- Chunking comparison: character vs semantic chunking report + metrics

➡️ Repo: `solara-ds`  
➡️ Proof docs to open:
- `EVALUATION_RESULTS.md`
- `CHUNKING_METRICS_COMPARISON.txt`

---

### 3) Atlas Advanced Watchlist — static topics + Teams updates
**Goal:** monitor a fixed watchlist, dedupe stories, generate briefs, notify Teams.

**Proof artifacts:** runnable pipeline + web UI + Teams notifier.
- Runs topics in **watchlist mode** and sends updates via **Incoming Webhook**
- Includes a simple web UI to run pipeline + view briefs

➡️ Repo: `Atlas-Advanced-Watchlist`  
➡️ Doc to open: `WEB.md`

---

## Dashboards & SQL projects (quick proof)
- **Sales Analytics Dashboard (Power BI + MySQL dump):** `sales-analytics-dashboard-powerbi`
- **COVID analysis (SQL + Tableau prep outputs):** `covid-data-analysis-sql-tableau`
- **Real estate cleaning (MySQL cleaning script):** `real-estate-data-cleaning-mysql`

---

## Skills (only what’s used in repos)
**Python:** pandas, numpy, scikit-learn, Flask/FastAPI, pytest  
**SQL:** MySQL (cleaning + analysis scripts), database dumps for BI work  
**BI:** Power BI dashboards (PBIX + prepared datasets)  
**RAG:** chunking, retrieval, citation handling, evaluation (RAGAS), guardrails

---

## Currently learning (not counted as project experience)
- Advanced SQL (window functions, performance tuning, warehousing patterns)
- Tableau dashboard UX best practices
