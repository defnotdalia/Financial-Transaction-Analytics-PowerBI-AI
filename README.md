# Financial-Transaction-Analytics-PowerBI-AI

## Overview
This project presents a comprehensive Business Intelligence dashboard created in Power BI to analyze a banking transaction dataset. This project leverages a modern, AI-augmented approach, utilizing **SQL** for robust data preparation and **Perplexity AI** for generating data, structuring SQL queries, and providing recommendations for key performance indicators (KPIs), charts, and DAX measures.

The resulting interactive dashboard provides critical insights into monthly transaction trends, customer demographics, and financial balances.

## Key Features & Technology Stack

* **Business Intelligence Tool:** Power BI
* **Data Generation:** Perplexity AI
* **Data Modeling & Preparation:** SQL Joins (to combine three distinct tables)
* **Advanced Analytics:** DAX formulas (recommended by Perplexity)
* **Project Management:** Git/GitHub

## Data & Methodology

The core data for this report was initially created and structured using **Perplexity AI** and loaded into a database environment.

### Data Preparation Steps:
1.  **Data Generation:** Initial mock data was generated using **Perplexity AI** to ensure a realistic dataset for the banking domain.
2.  **SQL Integration:** Three separate data tables were combined and cleaned using a series of **SQL Joins** to form a single, cohesive data model ready for Power BI.
3.  **AI-Guided Recommendations:** **Perplexity AI** was used to suggest relevant KPIs, effective chart types, and complex DAX measures to maximize the analytic value of the report.

## Dashboard Insights & Visualizations

The Power BI report focuses on key areas of banking performance, including transaction volume, balance changes, and customer profiles.

### Key Performance Indicators (KPIs)
* **Monthly Transaction Trend:** Analyzing transaction volume over the year.
* **Customer Demographics:** Segmenting customers by age group and gender.
* **Balance Analysis:** Tracking the overall transaction balance and identifying individual high-impact accounts.

### Featured Visualizations (As seen in the report)
* **Monthly Transaction Amount by Month:** Shows high transaction periods in **June (\$3.99M)**, **July (\$3.97M)**, and **October (\$3.93M)**, with a significant trough in **August (\$0.81M)**
* **Monthly Transaction Balance by Month:** Highlights periods of large net outflows, with the lowest overall transaction balance recorded in **October (\$-1.89M)**
* **Transaction Type Split:** Transactions are split evenly, with **50% DEBIT** and **50% Credit**
* **Customer Age Group:** The largest customer segment falls within the **36-50 age group** (200 customers).
* **Total Balance by Name:** Notably identifies the account for **"priya singh"** with a substantial negative balance **(\$-15,787.44K)**.
2.  **Open the File:**
    * Download and install **Power BI Desktop**.
    * Open the `Banking Dataset PowerBI Report.pbix` file from the cloned directory to interact with the full dashboard and data model.
