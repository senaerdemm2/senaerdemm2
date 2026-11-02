# Hi, I'm Sena 👋

### Computer Engineering Graduate | Data Analytics · BI · Automation | Python · SQL · Power BI · Excel

Computer Engineering graduate with 1 year of experience in e-commerce data analytics. I build end-to-end data pipelines in Python and SQL, validate data quality, and turn the results into dashboards and clear recommendations, from churn and marketing analysis to automated KPI reporting in Power BI.

I’m looking for entry-level roles in Data Analytics, BI and Reporting, and I’m also open to Software QA and Technical Support roles where my Python and data validation background fits.

---

## 📌 At a Glance

| | |
|---|---|
| **Status** | Computer Engineering grad (April 2026) · Open to Junior Data Analyst, BI Analyst and Reporting Analyst roles |
| **Experience** | 1 year Data Analyst @ SOFTCOUNT (Remote, US) · Amazon e-commerce analytics |
| **Projects** | 4 end-to-end projects across SQL · Power BI · Python |
| **Data handled** | 300K+ records across e-commerce, IT support and HR survey data |
| **Core stack** | SQL (PostgreSQL) · Python (Pandas, SciPy) · Power BI (DAX, Power Query) · Power Automate |
| **Certifications** | HackerRank SQL (Basic → Advanced) · Data Analysis Certificate, TechPro Education |
---

## 📑 Table of Contents

- [About](#about)
- [Experience](#experience)
- [Portfolio Projects](#portfolio-projects)
  - [IT Support Ticket Analysis & Weekly Automated Reporting](#it-support-ticket-analysis--weekly-automated-reporting)
  - [Olist E-Commerce Business Analytics Dashboard](#olist-e-commerce-business-analytics-dashboard)
  - [Post-Pandemic Remote Work & Health Impact Analysis](#post-pandemic-remote-work--health-impact-analysis)
  - [Student Habits & Academic Performance Analysis (Thesis)](#student-habits--academic-performance-analysis-thesis)
- [Education](#education)
- [Technical Skills](#technical-skills)
- [Certifications & Languages](#certifications--languages)
- [Contact](#contact)

---

## About
## About

I'm a Computer Engineering graduate based in Kraków with 1 year of experience as a Data Analyst in e-commerce analytics. I work mainly with SQL, Python and Power BI.

In my work, I built a Python pipeline that combined 36 data sources (230K+ Amazon orders) with automated data-quality checks, and it caught a revenue error that would have inflated results by up to 26x. I then used that data to explain why sellers were cancelling their subscriptions and where ad spend was being wasted.

My projects follow the same approach: start from a real business question (SLA performance, revenue concentration, employee burnout), clean and validate the data, and deliver the answer as a clear dashboard or automated report.

I'm looking for Junior Data Analyst, BI Analyst or Reporting Analyst roles where careful work with data has a direct impact on decisions.



---

## Experience

### Data Analyst
**SOFTCOUNT** · Remote (New York, USA) · Sep 2025 – Sep 2026
*Amazon e-commerce analytics*

- Built an end-to-end Python pipeline (Pandas, SciPy) integrating 36 raw sources (230K Amazon orders, 61K Keepa listings, ad data and 8.3K subscriber accounts) with automated data-quality checks; caught a field-definition error that inflated multi-unit revenue by up to 26x.
- **Churn analysis:** found that sellers who never listed a product cancelled at 85% vs 57% and drove 63% of all cancellations, pointing to onboarding as the main retention lever.
- **Marketing analytics:** audited four months of Meta and Google ad spend and traced a 69% rise in CPA mainly to a 31% drop in purchases per click; recommended daily spend caps and funnel fixes before scaling budget.
- **Top seller analysis:** analyzed 61K listings from 12 top sellers; best-ranked listings had 35x more reviews and 3x the FBA share (75% vs 24%).
- **Segment analysis:** showed Mexico delivered 49% of profit from 39% of orders, and proposed A/B tests to confirm causal levers.
- **Data modeling:** delivered a data dictionary, a star-schema model, an ETL proposal, BI-ready datasets and 13 prioritized data requests to management.

---

## Portfolio Projects

### IT Support Ticket Analysis & Weekly Automated Reporting

**Goal:** Build the full weekly reporting stack a support manager needs — from raw tickets in PostgreSQL to a Power BI dashboard delivered automatically to the inbox every Monday at 09:00 via Power Automate.


👉 [**View Project →**](https://github.com/senaerdemm2/it-support-ticket-analysis)

**Description:** End-to-end pipeline for 5,000 IT support tickets — PostgreSQL storage → Power Query cleaning → Power BI star schema → automated weekly KPI summary email via Power Automate.

**Skills:** SQL conditional aggregation (`CASE WHEN`, `GROUP BY`), Power Query M (deduplication, Trim + Capitalize, custom columns), DAX measures (`DIVIDE`, `AVERAGE`, `CALCULATE`), star-schema modeling, reporting automation.

**Technology:** PostgreSQL · Power Query · Power BI · DAX · Power Automate

**Results:**
- **SLA Met %: 82.1%** platform-wide (17.9% breach)
- **Avg resolution: 16.9 hrs** — surfaced per category and per team
- DAX KPI measures: SLA Met %, Avg Resolution Hours, Open Tickets, Avg CSAT
- Automated weekly KPI summary live every Monday 09:00 Europe/Warsaw

---

### Olist E-Commerce Business Analytics Dashboard

**Goal:** Surface actionable commercial and operational insights from 99K Brazilian e-commerce orders for executive leadership — through a 2-page Power BI dashboard.


👉 [**View Project →**](https://github.com/senaerdemm2/olist-ecommerce-analysis)

**Description:** ~99,000 Olist orders (2016–2018) analyzed in PostgreSQL and visualized in a 2-page Power BI dashboard with DAX, disconnected tables, and dynamic measures. Six business questions answered, each mapped to a dashboard visual and a recommended action.

**Skills:** SQL (joins, CTEs, window functions, aggregation), DAX (disconnected tables, `SWITCH` + `SELECTEDVALUE`, dynamic measures), Power BI data modeling, enriched tooltips, executive storytelling.

**Technology:** PostgreSQL · SQL · Power BI · DAX · Power Query

**Results:**
- **São Paulo = 37% of revenue** — single-market dependency flagged
- **Top 3 states = 63% of revenue** — expansion upside identified in BA (29% higher AOV than SP)
- Built dynamic Revenue/Orders view using DAX `SWITCH` and disconnected table
- Drove market-expansion recommendations from concentration analysis

---

### Post-Pandemic Remote Work & Health Impact Analysis

**Goal:** Statistically validate how remote, hybrid, and onsite work arrangements impact employee health — using a 2025 post-pandemic survey of 3,157 responses across 6 regions.


👉 [**View Project →**](https://github.com/senaerdemm2/remote-work-health-analysis)

**Description:** Full EDA workflow with formal hypothesis testing (chi-square, ANOVA, t-tests), effect size quantification (Cramér's V, eta-squared, Cohen's d), interactive Plotly visualizations, and a composite burnout risk score for employee segmentation.

**Skills:** EDA, statistical hypothesis testing, effect size analysis, feature engineering (composite risk score), interactive Plotly visualizations.

**Technology:** Python · Pandas · SciPy · Plotly · ydata-profiling

**Results:**
- **3,157 responses across 6 regions** — Remote 18.6%, Hybrid 31.9%, Onsite 49.5%
- Statistically significant relationships validated with **chi-square + Cramér's V, ANOVA + eta², t-test + Cohen's d (95% CI)**
- Engineered **burnout risk score** for high-risk employee segmentation

---

### Student Habits & Academic Performance Analysis (Thesis)

**Goal:** Determine how lifestyle factors affect academic performance — using a dataset of 1,000 student records with 16 features.


👉 [**View Project →**](https://github.com/senaerdemm2/student-habits-academic-performance-analysis)

**Description:** EDA and statistical analysis validating lifestyle–performance relationships via hypothesis testing. Built a Linear Regression pipeline and presented findings in an interactive Power BI dashboard.

**Skills:** Hypothesis testing, regression modeling, feature analysis, Power BI storytelling.

**Technology:** Python · Pandas · Scikit-Learn · SciPy · Power BI

**Results:**
- Analyzed **1,000 student records** with **16 features**
- Built **Linear Regression pipeline with R² = 0.90**
- Presented findings in an interactive Power BI dashboard

---

## Education

**B.Sc. in Computer Engineering** · *Vistula University, Warsaw, Poland* · Oct 2022 – Apr 2026

**Erasmus Exchange** · *HTW Dresden, Germany* · Sep 2024 – Feb 2025

---

## Technical Skills

**Data Analytics & BI:** Power BI · DAX · Power Query · KPI Reporting · Power Automate · Azure

**SQL & Databases:** SQL · PostgreSQL · CTEs · JOINs · Aggregations · `CASE WHEN`

**Python & Visualization:** Python · Pandas · Numpy · SciPy · Scikit-Learn · Plotly

**Statistics:** Hypothesis Testing · Chi-square · ANOVA · t-test · Linear Regression

**Excel:** PivotTables · XLOOKUP · IF Functions · Conditional Formatting · Data Cleaning

**Tools:** Jupyter Notebook · Git

---

## Certifications & Languages

**Certifications:**
- HackerRank SQL (Basic, Intermediate, Advanced)
- Data Analysis Certificate - TechPro Education

**Languages:**
- English (B2)
- Turkish (Native)

**Volunteer:** Turkish Cultural Events, Warsaw (Oct 2024 – July 2026)

---

## Contact

- 📧 Email: [sena.erdem.pl@gmail.com](mailto:sena.erdem.pl@gmail.com)
- 💼 LinkedIn: [sena-erdem](https://www.linkedin.com/in/sena-erdem-a64b91345/)
- 🌐 Portfolio: [senaerdemm.vercel.app](https://senaerdemm.vercel.app)
- 📞 Phone: +48 792 624 121
- 📍 Location: Kraków, Poland

