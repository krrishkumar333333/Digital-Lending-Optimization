# Digital Lending Portfolio Optimization 🏦

![Certificate](Digital_lending_portfolio_optimization.png)

*Certified by IIT Guwahati Summer Analytics*

## 📌 The Business Constraint
Digital lending platforms face a critical balance: approving enough loans to maximize interest revenue while maintaining strict risk thresholds to avoid massive default losses. The objective of this project was to build a predictive model that identifies high-risk applicants before capital is deployed.

## ⚙️ The Technical Architecture
* **Algorithm:** Gradient Boosting (XGBoost/CatBoost) Ensembles
* **Feature Engineering:** Synthesized custom risk metrics combining credit history, debt-to-income ratios, and temporal employment data.
* **Evaluation Metric:** F1-Score & ROC-AUC to heavily penalize false negatives (approving a guaranteed default).

## 🚀 Key Results & Impact
* Developed a risk-adjusted lending model to optimize approval thresholds and mitigate default rates.
* Identified latent features driving loan default, allowing for dynamic thresholding rather than static credit-score cutoffs.

## 📂 Repository Contents
* `Notebook.ipynb`: The end-to-end data pipeline, model training, and evaluation.
* `Executive_Report.pdf`: Comprehensive breakdown of the methodology and business recommendations.
