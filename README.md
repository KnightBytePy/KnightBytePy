<!-- ======================= -->
<!-- HERO / TOP BANNER AREA -->
<!-- ======================= -->
<p align="center">
<img src="https://media.giphy.com/media/GghGKaZ8JeHJx0apQC/giphy.gif" width="520px"/>
</p>



<h1 align="center">Hi, I'm Fares 👋</h1>

<p align="center">
  <b>Data Scientist @ McGill MDS | Applied ML & AI</b><br/>
  I build machine learning systems that real teams can actually use.
</p>

<p align="center">
  <a href="https://github.com/YOUR_USERNAME?tab=repositories">
    <img src="https://img.shields.io/badge/Code-Portfolio-black?style=for-the-badge&logo=github" />
  </a>
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" />
  </a>
  <a href="mailto:YOUR_EMAIL@email.com">
    <img src="https://img.shields.io/badge/Email-Let's%20Talk-red?style=for-the-badge&logo=gmail" />
  </a>
</p>

<p align="center">
  <b>Actively looking for Data Science / ML roles (Intern / New Grad 2026)</b>
</p>

---

## 🧠 What I Do
- End-to-end ML: data → features → model → dashboard → decision
- Forecasting and risk modeling in messy, high-stakes settings (retail demand, credit risk, portfolio allocation)
- Explainable ML for non-technical stakeholders (SHAP, what-if simulation)
- Reproducible delivery (Docker, VS Code Dev Containers)

---

## 🔥 Featured Projects
These are built like products, not class assignments.

### 1. Customer Churn Intelligence Dashboard
<p align="left">
  <!-- dashboard / analytics-style animated charts -->
  <img src="https://media.giphy.com/media/MZEIaQ799hT1VXMqz8/giphy.gif" width="400px"/>
</p>

**What it is**  
- Churn model using SMOTE + XGBoost (F1 on churners = 0.93)  
- Flags high-risk customers and simulates “what if we give this segment a 10% discount?”  
- Delivered in Streamlit so non-technical teams can use it

**Why it matters**  
- It's not “here’s a model,” it’s “here’s who to save today and how.”

**Repo:** [`customer-churn-streamlit`](https://github.com/YOUR_USERNAME/customer-churn-streamlit)

---

### 2. ChronosBlend: Retail Sales Forecasting Engine
<p align="left">
  <!-- animated stock/time-series style line trend -->
  <img src="https://media.giphy.com/media/w2hGxjfmUiI3uWkm1K/giphy.gif" width="400px"/>
</p>

**What it is**  
- Hybrid LSTM + Prophet + XGBoost forecaster on ~421k rows of Walmart-style weekly sales  
- Handles promo spikes, seasonal effects, macro signals

**How it's built**  
- Leakage-safe time-aware CV  
- Rolling / lag features  
- Holiday & promo awareness

**Why it matters**  
- Helps planners avoid stockouts during high-demand weeks

**Repo:** [`chronosblend-forecasting`](https://github.com/YOUR_USERNAME/chronosblend-forecasting)

---

### 3. Credit Risk Scoring + Explainability
<p align="left">
  <!-- neural-net / AI brain vibe -->
  <img src="https://media.giphy.com/media/25Itcrcuwkyq3ohubJ/giphy.gif" width="400px"/>
</p>

**What it is**  
- Default probability model with gradient boosting  
- SHAP explanations: “here’s exactly why this borrower is high risk”  
- Outputs risk tiers underwriter teams can defend to compliance

**Why it matters**  
- Turns “black box says no” into transparent, auditable reasoning

**Repo:** [`credit-risk-scoring`](https://github.com/YOUR_USERNAME/credit-risk-scoring)

---

### 4. Portfolio Optimizer Research (In Progress)
<p align="left">
  <!-- scrolling code / data stream vibe -->
  <img src="https://media.giphy.com/media/66M6ZwJkTLYikvhrqZ/giphy.gif" width="400px"/>
</p>

**What it is**  
- Scenario-driven allocation engine inspired by $500B+ AUM asset management scale  
- Multi-model risk integration + realistic transaction cost penalties  
- Goal: “If we shift 2% here, what happens to risk, cost, and exposure?”

**Status:** Private / request access

---

## 🛠 Tech Stack
```text
Core      : Python, SQL, Pandas, NumPy
Modeling  : Scikit-Learn, XGBoost, LightGBM, CatBoost
Deep/TS   : PyTorch, Keras (LSTM), Prophet
Apps      : Streamlit dashboards, FastAPI services
Infra     : Docker, VS Code Dev Containers
Explain   : SHAP / model interpretability
