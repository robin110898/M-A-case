M&A Impact Analysis: Alphabet Inc. (Google) Financial Performance (2004–2024)

📝 Project Overview

This repository contains the statistical analysis and research code for my Master's Thesis: "Effects of Mergers and Acquisitions on the Financial Performance and Strategy in the Global Tech Industry: The case of Alphabet Inc.".

The project investigates how 21 years of aggressive acquisition strategies (including landmark deals like YouTube, Motorola, and Fitbit) have influenced Alphabet Inc.'s core financial health. By utilizing Ordinary Least Squares (OLS) regression and rigorous diagnostic testing, this study quantifies the relationship between M&A intensity and profitability, liquidity, and solvency.

📊 Dataset & Variables

The analysis is based on a longitudinal dataset spanning from 2004 to 2024. Data was consolidated from FactSet, SEC filings (Form 10-K), and Alphabet’s official investor relations publications.
- Independent Variables (Predictors): Annual Number of Acquisitions (t and t-1), Annual M&A Spending (t and t-1), and Annual Revenue (as a control for firm size).
- Dependent Variables: 9 key financial ratios categorized into three dimensions:
  - Profitability: ROA, ROE, Net Profit Margin.
  - Liquidity: Current Ratio, Quick Ratio, Cash Ratio.
  - Solvency: Debt-to-Assets, Debt-to-Equity, Net Debt-to-Equity.

🛠 Methodology

The analysis follows a strict econometric workflow to ensure the reliability of results:
- Feature Engineering: Implementation of one-year lagged variables to capture the "gestation period" of acquisition synergies.
- Regression Modeling: Multi-model comparison (individual vs. aggregated ratios) using Ordinary Least Squares (OLS).
- Statistical Diagnostics: Validation of model assumptions including:
  - Multicollinearity: Variance Inflation Factor (VIF).
  - Heteroskedasticity: Breusch-Pagan Test.
  - Normality of Residuals: Jarque-Bera Test.
  - Autocorrelation: Durbin-Watson Statistic.

🚀 Key Findings
- Liquidity Strain: M&A activity shows a significant immediate negative impact on all liquidity ratios, as the firm redeploys cash for integration and investment.
- Profitability Lag: Short-term profitability often declines in the year following an acquisition (t-1) due to integration costs, though long-term strategic value is created as shown in the YouTube case study.
- Solvency Dynamics: M&A leads to a moderate increase in leverage, though overall solvency is primarily driven by revenue-based expansion rather than acquisition debt alone.
- Model Superiority: The 5-Variable Individual Ratios Model achieved the highest statistical reliability, with an 88.9% significance rate across the tested financial indicators.

🎓 Author
Dang Thi Hien
- University: Università degli Studi di Brescia, Italy.
- Department: Economics and Management.
- Degree: Master's in Management (International Business).
- Academic Year: 2025/2026.

_Disclaimer: This research is for academic purposes and utilizes publicly available financial data.__
