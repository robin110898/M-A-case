M&A Impact Analysis: The Case of Alphabet Inc. (2004–2024)

🔍 What It Is?

This project is a comprehensive financial econometric analysis that explores the long-term effects of Mergers and Acquisitions (M&A) on the performance of a global technology leader, Alphabet Inc.. Covering a 21-year trajectory from 2004 to 2024, the study examines how more than 250 strategic transactions—including the acquisitions of YouTube, Motorola Mobility, and Fitbit—have reshaped the company's financial health across three fundamental pillars:
- Profitability: Gauging efficiency through ROA, ROE, and Net Profit Margin.
- Liquidity: Assessing short-term cash flexibility via Current, Quick, and Cash Ratios.
- Solvency: Evaluating capital structure stability through Debt-to-Asset and Debt-to-Equity ratios.
  
💡 Why It Is?

In the fast-paced technology industry, M&A is often pursued as a "growth hack," yet the majority of deals fail to meet their intended objectives. This repository is essential for anyone interested in Data-Driven Finance or Strategic Management because:
- Empirical Evidence over Hype: It moves beyond business narratives to provide statistical proof of how M&A affects the bottom line.
- Understanding Temporal Lags: It demonstrates that the benefits of tech acquisitions are rarely immediate and often require a "gestation period" for integration.
- Investment Insight: It highlights the "Liquidity-Expansion Trade-off"—showing how aggressive growth can temporarily strain cash reserves.
- Real-World Success vs. Failure: Through comparative analysis (e.g., the success of YouTube vs. the challenges of Motorola Mobility), it offers a blueprint for effective post-merger integration.

🛠️ How It Works?

This analysis follows a rigorous scientific workflow, transforming raw financial data into actionable insights using modern analytical tools:
⚙️ Analytical Framework
- Data Engineering: Pre-processing 21 years of financial statements and implementing One-Year Lagged Variables to capture delayed integration effects.
- Econometric Modeling: Applying Ordinary Least Squares (OLS) Regression to quantify the strength and direction of M&A impacts.
- Diagnostic Validation: Ensuring statistical integrity through:
  - VIF Analysis: Testing for multicollinearity among predictors.
  - Breusch-Pagan Test: Detecting heteroskedasticity.
  - Durbin-Watson Statistic: Evaluating autocorrelation in time-series residuals.
  - Jarque-Bera Test: Confirming the normality of residuals.

🛠️ Toolstack

- Python: The core engine for data manipulation and statistical computing.
- Pandas & NumPy: For robust financial data cleaning and feature engineering.
- Statsmodels: For detailed OLS regression outputs and diagnostic tests.
- Matplotlib & Seaborn: For high-fidelity financial data visualizations and correlation heatmaps.
- Google Colab: The integrated development environment used for reproducibility.

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
