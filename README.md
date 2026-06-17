# ml-rfp-opportunity-ranking
Developed in 2025. An upgraded version of this project idea developed in 2026 can be found here: https://github.com/i-polymath/bd-opportunity-prioritization-system

# AI-Powered RFP Opportunity Identification & Ranking System

## Overview

This project develops a machine learning solution to automate the identification and prioritization of procurement opportunities for consulting firms.

The solution was designed as part of a business case focused on the Management and Economics Consulting industry, where business development teams spend significant time manually reviewing Requests for Proposals (RFPs).

Using historical procurement data from the World Bank, the project builds predictive models capable of estimating the likelihood of proposal success and ranking opportunities accordingly.

---

## Business Problem

Consulting firms rely heavily on responding to RFPs to generate revenue.

Business development teams often:

- Search multiple procurement portals manually
- Evaluate opportunities based on subjective judgment
- Spend significant effort on low-probability bids
- Miss relevant opportunities due to time constraints

This project explores how Machine Learning can improve opportunity identification and proposal prioritization.

---

## Objectives

- Automate opportunity discovery
- Predict proposal success probability
- Reduce manual business development effort
- Improve proposal win rates
- Support data-driven bid/no-bid decisions

---

## Dataset

Source:
World Bank Corporate Procurement Contract Awards Dataset: https://financesone.worldbank.org/corporate-procurement-contract-awards/DS00028?_gl=1*1wwb4pk*_gcl_au*MTY3NDU0NTkzMi4xNzIwNDY5OTQ1

The dataset was transformed to represent a hypothetical consulting firm's historical proposal database.

Additional feature engineering included:

- Country extraction from project descriptions
- Region and sub-region classification
- Synthetic generation of unsuccessful proposals
- Proposal status classification (Won / Lost)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Machine Learning Pipeline

### Data Preparation

- Data cleaning
- Country extraction
- Region assignment
- Synthetic target generation

### Exploratory Data Analysis

- Proposal distribution
- Geographic analysis
- Contract value analysis

### Feature Engineering

- Has 'Known Country' indicator
- Proposal Status
- Region classification

### Model Development

1. Logistic Regression
2. Random Forest Classifier

### Model Evaluation

Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

## Results

| Model | Accuracy | ROC-AUC |
|---------|---------|---------|
| Logistic Regression | 66.8% | 0.51 |
| Random Forest | 68.9% | 0.64 |

Random Forest was selected as the preferred model due to its stronger classification performance and ability to identify both successful and unsuccessful proposals.

---

## Business Impact

Concept estimated annual savings:

- 168 hours saved per week
- ~$756,000 annual labor savings

Additional benefits:

- Faster opportunity identification
- Improved proposal prioritization
- Better resource allocation
- Increased competitiveness

---

## Future Improvements

- NLP using BERT embeddings
- XGBoost implementation
- Real-time RFP scraping
- Automated proposal recommendations
- Dashboard deployment

---

## Author

Pascal Chisom Okechukwu
(Senior Associate – Data Analytics, Genesis Analytics Pty Ltd)
Master of Business Analytics and Data Science | EU Business School, Barcelona
(2025)
