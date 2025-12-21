# Week 03 — Churn Prediction (StreamWorks Media)

## Overview
StreamWorks Media faces rising acquisition costs, making retention critical. This project analyses `streamworks_user_data.csv` to identify churn drivers and build predictive models (Logistic Regression for churn; Linear Regression for tenure/loyalty signals) to support early intervention.

## Business Questions
- Do promotions reduce churn likelihood?
- Does watch time impact churn risk?
- Are heavy mobile users more likely to churn?
- Which factors drive churn most strongly?
- Which segments should retention prioritise?
- Can demographics predict tenure/loyalty?

## Method Summary
- Cleaned missing values and corrected date formats for modelling reliability.
- Engineered behavioural features to capture lifecycle and UX friction:
  - Tenure (days)
  - Loyalty flag (active > 180 days)
  - Heavy mobile user flag (> 70% app usage)
- Used statistical tests to validate observed differences and model coefficients to confirm directional impact.

## Model Performance (high level)
- **Logistic Regression (churn):** AUC reported and interpreted with a practical focus on recall for early warning.
- **Linear Regression (tenure):** Negative R² reported and explained as evidence that demographics alone are not sufficient; behaviour drives retention.

## Key Insights (high level)
- Engagement is a major retention lever: churners show substantially lower watch time than retained users.
- Mobile-dominant users show higher churn risk, indicating likely UX or experience friction.
- Prioritising recall identifies high-risk users, but false positives require low-cost interventions.

## Recommendations
- Trigger engagement nudges when watch time drops below a practical threshold (e.g., < 25 hours).
- Investigate mobile app friction points driving higher churn among heavy mobile users.
- Use “soft” interventions (personalised recommendations, watch-next prompts) to manage false positives.
- Reserve costly discounts for the highest-confidence churn risk segment.

## Files
- `notebook_week3.ipynb` — modelling workflow, charts, and evidence
- `coversheet_week3.pdf` — final written submission (primary graded artefact)
- `data/` — dataset used (if included)
- `brief/` — project brief (if included)
- `assets/` — screenshots used in reporting (optional)

## How to Run
Open `notebook_week3.ipynb` in Jupyter/Colab and run top-to-bottom.  
If datasets are not included in this repo, adjust file paths to your local copies.
