# Week 01 — Customer Sign-Up Behaviour & Data Quality Audit

## Overview
This project analyses customer sign-up behaviour and support ticket patterns to assess data quality and extract actionable insights for product, marketing, and operations teams. The focus is on identifying trends, segment differences, and data gaps that may affect decision-making.

## Business Questions
- What does sign-up behaviour look like across time (weekly/monthly trends)?
- Which customer segments appear most engaged or at higher risk of churn?
- What data quality issues (missingness, inconsistent categories, unknowns) could distort reporting?
- What support themes (e.g., login, billing) suggest friction points in the customer journey?

## What I Delivered
- Data quality audit (missing values, inconsistent categories, “Unknown” coverage)
- Feature engineering for reporting-ready analysis (e.g., signup week/month, age bands)
- Summary insights grounded in evidence and limitations
- Recommendations aimed at reducing friction and improving measurement

## Key Insights (high level)
- Customer acquisition is diverse, but engagement and responsiveness vary by segment.
- Support friction is concentrated in a few recurring issue types, indicating clear product/UX priorities.
- “Unknown” categories and unlinked tickets reduce segmentation accuracy and should be addressed.

## Recommendations
- Improve data capture to reduce “Unknown” categories and increase linkage between customers and tickets.
- Prioritise product fixes for the highest-volume friction areas (e.g., login/billing).
- Use segmentation (age bands, region where reliable) to tailor acquisition and retention messaging.

## Files
- notebook_week1.ipynb — original analysis workflow
- notebook_week1_portfolio.ipynb — refined, portfolio-ready notebook
- coversheet_week1.pdf — original submission
- coversheet_week1_portfolio.pdf — portfolio-ready report
- data/ — datasets used (if included)
- brief/ — project brief (if included)


## How to Run
Open `notebook_week1.ipynb` in Jupyter/Colab and run top-to-bottom.  
If datasets are not included in this repo, adjust file paths to your local copies.
