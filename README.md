# Consumer Shopping Behavior Analysis

## Overview
This project analyzes retail consumer shopping data to help management understand shifting purchasing patterns across demographics, product categories, and sales channels (online vs. offline). The analysis identifies key drivers of customer decisions and repeat purchases—including discounts, product reviews, seasonality, and payment preferences—to improve sales, customer satisfaction, and long-term loyalty.

## Overarching Business Question
> *"How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?"*

## Project Deliverables & Workflow
1. **Data Preparation & Modeling (`Python`)**
   - Cleaned, validated, and transformed the raw consumer dataset for downstream analysis.
   - Engineered features for customer demographics, seasonal trends, and discount sensitivity.
2. **Data Analysis (`SQL`)**
   - Structured the cleaned dataset into relational tables and simulated business transactions.
   - Queried customer segments, repeat-purchase behavior, loyalty indicators, and channel performance.
3. **Interactive Dashboard (`Power BI`)**
   - Built an interactive dashboard highlighting revenue trends, category performance, online vs. offline splits, and key purchase drivers.
4. **Executive Report & Presentation**
   - Summarized analytical findings and actionable marketing/product recommendations for stakeholders.

## Repository Structure
```text
├── data/               # Raw and cleaned datasets
├── scripts/            # Python scripts for data cleaning and transformation
├── sql/                # SQL queries for schema setup, segmentation, and KPI analysis
├── dashboard/          # Power BI (.pbix) dashboard file and visual exports
├── reports/            # Project summary report and stakeholder presentation deck
└── README.md
```

## Tech Stack
- **Data Cleaning & Modeling:** Python (Pandas, NumPy)
- **Querying & Segmentation:** SQL
- **Data Visualization:** Power BI
- **Documentation:** Markdown, PowerPoint / PDF

## How to Use
1. Clone the repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/consumer-shopping-behavior-analysis.git
   ```
2. Run the data preparation scripts in `scripts/` to generate the processed dataset.
3. Execute the queries in `sql/` against your database instance to reproduce the segment and driver metrics.
4. Open the `.pbix` file in `dashboard/` using Power BI Desktop to explore the interactive visuals.