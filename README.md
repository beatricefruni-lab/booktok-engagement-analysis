# booktok-engagement-analysis
Python data science project analyzing TikTok engagement through psycholinguistics and OLS regressions.

# Multimodal & Psycholinguistic Analysis on BookTok Engagement

An end-to-end Data Science project based on my Master's Thesis, analyzing social media engagement within the publishing industry.

## Project Overview
This project investigates how linguistic framing (psycholinguistics) and structural video features impact user engagement on TikTok (specifically the "BookTok" community). The analysis focuses on the Italian market ($N=346$ observations).

## Methodologies
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Statsmodels
- **Text Analysis:** LIWC2007 (Linguistic Inquiry and Word Count)
- **Econometrics:** Multiple Linear Regression (OLS), Multicollinearity diagnostics (VIF & Pearson Correlation)

## Key Findings
- Successfully identified and resolved critical multicollinearity among superficial metrics (Likes, Comments) using the **Variance Inflation Factor (VIF)**.
- Isolated "Views" as an algorithmic control variable.
- Proved that user-oriented linguistic framing (e.g., the use of the pronoun "You") has a positive, statistically significant impact on **Saves**, which serves as the strongest proxy for consumer purchase intent.
