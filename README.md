# Portfolio Analytics & Asset Intelligence Engine

An enterprise-grade, end-to-end data engineering and business intelligence solution. This project designs a robust ETL pipeline using Python to ingest and transform raw transactional data into an enriched financial schema, ultimately deploying an executive-facing interactive reporting framework in Power BI.

---

## 🔗 Project Access Points
* 📊 **[Interactive Executive Dashboard](PASTE_YOUR_POWER_BI_SERVICE_LINK_HERE)** — *Explore the live, production-ready 4-page Power BI asset intelligence workspace.*
* 💻 **[Data Engineering Pipeline (Google Colab)](PASTE_YOUR_COLAB_SHARE_LINK_HERE)** — *Review the production-ready Python orchestration script, data validation, and modeling logic.*

---

## 🔬 Core Architectural Blueprint (AART Framework)

* **Strategic Objective (Aim):** To architect a scalable analytics pipeline that ingests flat transactional records and transforms them into a feature-engineered financial data model to fuel a multi-page executive BI architecture.
* **Technical Execution (Action):** Programmed automated ETL scripts in **Python** utilizing a cloud-hosted **Google Colab** environment. Normalized raw temporal fields, engineered relative transactional yields, modeled automated drag-coefficients using asset expense thresholds, and computed non-linear performance efficiency metrics across distinct asset classes.
* **Business Impact (Result):** Successfully engineered a 1,000-record high-fidelity database, seamlessly integrated via a star-schema data model into a 4-page **Power BI** application, empowering portfolio managers to identify systemic cost drags and monitor macro performance trends.
* **Technology Stack:** Python (Pandas, NumPy), Google Colab, Microsoft Excel, Power BI Service.

---

## 🛠️ Data Modeling & Feature Engineering Roadmap

The transaction ledger was enriched inside the Python execution layer to generate high-utility calculated metrics for advanced down-stream filtering:
* **📅 Temporal Expansion:** Discretized linear transaction dates into distinct macro dimensions (`Investment_Year`, `Investment_Quarter`, `Investment_Month_Name`) to support micro-level time-series filtering.
* **💰 Margin Optimization:** Calculated net portfolio appreciation values (`Net_Absolute_Profit_INR`) by quantifying variance between asset cost bases and market valuations.
* **📉 Yield Drag Quantification:** Modeled automated financial drag variables (`Annual_Expense_Cost_INR`) by calculating expense thresholds against active capitalization.
* **📊 Structural Efficiency Weighting:** Formulated a proprietary `Asset_Efficiency_Index` to evaluate risk-adjusted return velocity relative to active operational costs.

---

## 📊 Analytics Visualization Architecture
The reporting layer translates the underlying analytical schema into a cohesive narrative, separating core investment categories into high-impact visual segments:

* **📊 Benchmark Indexes:** Aggregates macro tracking statistics for broad market exposures (50 benchmark metrics).
* **🎯 Sectoral & Thematic Clusters:** Isolates industry-specific alpha engines across highly cyclical markets (30 targeted variables).
* **🥇 Alternative Hedging Assets:** Monitors portfolio volatility counter-weights through precious metal tracking metrics (5 core positions).

---

## 📂 Repository Topology
```text
├── data/
│   ├── raw_investments.csv          # Inbound transactional source data
│   └── enriched_portfolio.xlsx      # Feature-engineered production schema
├── notebooks/
│   └── portfolio_engineering.ipynb    # Python ETL & data orchestration notebook
├── dashboards/
│   └── asset_intelligence.pbix      # Local Power BI application file
└── README.md                        # Portfolio documentation page
```
