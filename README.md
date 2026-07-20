# Netflix Ads Analytics Portfolio Project

![Top Titles for Ad Placement](Images/Top_Titles.png)  <!-- Add your screenshot here -->

**End-to-End Analytics Engineering Project** simulating ad platform insights for Netflix's Ads Data Science & Engineering team.

## Business Objective
Build metrics, deep-dive analysis, and self-service tools to support decision-making in Netflix's ad-supported tier (0-1 space).

## What I Built
- Ingested and cleaned large Netflix content + 2025-2026 viewership datasets
- Created custom **Ad Opportunity Score** combining duration, recency, ratings, and actual hours viewed
- Merged metadata with real top-viewed titles
- Generated insights on best content for ad placement
- Prepared data for interactive Power BI dashboards

## Data Sources
See [data_download.md](data_download.md) for download links and setup instructions.

## Tech Stack
- **Python** (Pandas, Matplotlib, Seaborn) – ETL & Analysis
- **Jupyter Notebooks** – Exploration
- **Git + GitHub** – Version control
- **Power BI** / Microsoft Fabric

## Key Insights
- Analyzed **32,000+ Netflix titles** (up to 2025) combined with **2025–2026 Top 500 global viewership data**
- Created custom **Ad Opportunity Score** prioritizing actual hours viewed, duration, recency, and trending performance
- **Top Titles**: KPop Demon Hunters (#1 with massive viewership), Back in Action, Frankenstein, etc.
- **Top Genres**: War, Science Fiction, Romance, and Action-heavy content show strongest ad potential

## How to Run
1. `git clone` this repo
2. `python -m venv venv && venv\Scripts\activate`
3. `pip install -r requirements.txt`
4. Open `notebooks/01_data_exploration.ipynb`

