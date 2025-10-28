<p align="center">
  <img src="./assets/terminal_wave.gif" width="400px"/>
</p>

<h1 align="center">Fares Jony</h1>

<p align="center">
  <b>Applied Machine Learning & Data Science @ McGill</b><br/>
  Forecasting • Risk Modeling • Churn Prevention • GenAI Assistants
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-Production--Ready-success?style=flat-square&logo=python" />
  <img src="https://img.shields.io/badge/Forecasting-Temporal%20CV%20%7C%20LSTM%20%2B%20Prophet-blueviolet?style=flat-square" />
  <img src="https://img.shields.io/badge/Explainability-SHAP%20Insights-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Reproducible-Dockerized-lightgrey?style=flat-square&logo=docker" />
</p>

<p align="center">
  <b>Open to Data Science / ML roles (Intern / New Grad 2026)</b>
</p>

---

## 🚀 I Build ML That People Can Use
- End-to-end: ingestion → feature engineering → model → explainability → dashboard
- Not just “accuracy,” but “can the business act on this today”
- Focused on high $ impact use cases: retention, credit risk, inventory, allocation

---

## 🔬 Core Projects

### 🟣 Customer Churn Prediction + Retention Simulator
<p float="left">
  <img src="./assets/churn_dashboard.gif" width="420px"/>
</p>

**What it does**  
- Predicts which customers are about to churn (SMOTE + XGBoost)  
- F1 = 0.93 on churners (so we catch the at-risk group)  
- Streamlit dashboard where managers can test “What if I offer a 10% discount / free month / upgrade?”

**Why it matters**  
- This is built like a tool a retention team would actually use tomorrow

**Code**  
[`customer-churn-streamlit`](https://github.com/YOUR_USERNAME/customer-churn-streamlit)

---

### 🔵 ChronosBlend Retail Forecasting Engine
<p float="left">
  <img src="./assets/chronosblend_forecast.gif" width="420px"/>
</p>

**Goal**  
Forecast weekly sales for 45+ stores × departments (~421k rows), including promo spikes and seasonal events.

**How**  
- Hybrid ensemble:
  - LSTM (short-term patterns)
  - Prophet (seasonality, holidays)
  - XGBoost (tabular price/promo/macro signals)
- Time-aware CV and leakage-safe feature design

**Why it matters**  
- Stock the right SKU in the right store at the right week

**Code**  
[`chronosblend-forecasting`](https://github.com/YOUR_USERNAME/chronosblend-forecasting)

---

### 🟠 Credit Risk Scoring + SHAP Explainability
<p float="left">
  <img src="./assets/shap_anim.gif" width="420px"/>
</p>

**Goal**  
Score borrower default risk and surface *why* they’re risky.

**How**  
- Gradient boosting model (XGBoost / CatBoost)
- SHAP to generate human-readable rationales
- Risk tiers for underwriting & compliance

**Why it matters**  
- Moves the conversation from “the model said no” to “here are the top 3 risk drivers for this applicant”

**Code**  
[`credit-risk-scoring`](https://github.com/YOUR_USERNAME/credit-risk-scoring)

---

### 🟢 Portfolio Optimizer Research Platform
**Context**  
- Inspired by $500B+ AUM asset management workflows  
- Multi-model risk integration (Bayesian mixtures, worst-case risk), transaction cost modeling

**Why it matters**  
- Helps PMs explore “What happens if we shift 2% into this asset?” with explainable tradeoffs  
- Built for real allocation decisions, not just a Markowitz homework plot

**Status**  
Private / in progress

---

## 🧰 My Stack
```text
Languages      : Python, SQL
ML / Model Dev : scikit-learn, XGBoost, LightGBM, CatBoost
Deep Learning  : PyTorch, Keras (LSTM), Prophet
Forecasting    : Feature-rich time series, temporal CV, leakage control
Apps           : Streamlit dashboards, FastAPI services
Infra          : Docker, VS Code Dev Containers
Explainability : SHAP
