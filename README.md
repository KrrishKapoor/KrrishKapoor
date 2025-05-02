# 👋 Hey, I’m Krrish Kapoor

🎓 **Final-year BBA** student at the Schulich School of Business, specializing in **Business Analytics & Finance**  
📍 **Toronto, Canada** | 🔎 **Open to Analyst roles in Data · Finance · Strategy**

I’m passionate about turning raw data into actionable insights—especially where money, markets, and motorsport intersect.  
Whether it’s simulating retirement strategies, flagging fraudulent transactions, or predicting customer churn, I love projects that pair rigorous modeling with clear business impact.

---

## 🔎 About Me

- 📊 **Data-Driven Thinker** Skilled in **SQL · R · Python · Excel** for simulations, financial models, dashboards, and deep-dive analyses.  
- 📈 **Finance-Focused Analyst** Grounded in investments, forecasting, risk management, and optimization techniques.  
- 💡 **Problem-Solver & Collaborator** Thrive in cross-functional teams, case comps, and startup environments; comfortable presenting to execs and entrepreneurs.  

---

## 📁 Featured Projects

Below are my three flagship projects. Each link opens the repo with code, notebooks, and a walk-through of the analysis.

---

### 1️⃣ [OAS / CPP Optimization Simulator](https://github.com/KrrishKapoor/OAS-Strategy-Simulation) 

**Why it matters**  
Canadian retirees face a tricky puzzle: draw down their CPP and Old Age Security (OAS) too early and they miss out on guaranteed bumps; wait too long and they risk claw-backs and portfolio shortfalls. My simulator quantifies that trade-off so planners can make evidence-based recommendations.

**What I built**  
* **100,000+ Monte Carlo runs** modeling equity/bond paths, inflation, and longevity risk  
* **Dynamic tax engine** (Federal + Ontario) that applies marginal brackets, credits, and OAS claw-back rules in every future year  
* **Policy levers**: vary CPP start age, OAS deferral, RRSP/RRIF withdrawal order, TFSA taps, and glide-path equity shifts  
* **KPIs**: after-tax income, probability of ruin, median estate value, and Gini risk metrics  
* **Visual dashboard** (RMarkdown + ggplot2) that lets advisors toggle parameters and instantly see new distributions  

**Impact & results**  
* Optimal strategy (CPP at 70, OAS at 68, tax-efficient withdrawal order) lifts median after-tax income **+9 %** vs. “take CPP/OAS at 65” baseline  
* Reduces 10 %-tail shortfall risk by **≈15 %** for low-income retirees  
* Currently being pilot-tested in a capstone consulting project with a Toronto wealth-management firm  

**Tech & skills**  
`R`, tidyverse, data.table, actuarial math, Monte Carlo simulation, statistical graphics, personal-tax modeling

---

### 2️⃣ [Credit-Card Fraud Detection](https://github.com/KrrishKapoor/credit-card-fraud-detection)

**Business context**  
Every fraudulent Visa transaction costs the issuer \$10–\$40 in chargebacks and investigation overhead. Catching bad actors *before* settlement is pure bottom-line protection.

**Solution overview**  
1. **Data ingestion & prep** – anonymized European card dataset (284,807 rows; 492 frauds)  
2. **Severe class imbalance handling** – tried SMOTE, borderline-SMOTE, and cost-sensitive loss; selected cost-sensitive **Random Forest** as champion model  
3. **Feature engineering** – transaction time-band, rolling mean of amount per card, V-component PCA stability check  
4. **Model performance**  
   * ROC-AUC = **0.985**  
   * Precision@0.3% alert rate = **71 %** (industry benchmark ≈55 %)  
5. **Operations playbook** – probability threshold tuning to balance false-positives vs. investigation headcount; estimated **\$125 K annual savings** on a 1 M-tx daily volume firm.  

**Tech & skills**  
`Python`, pandas, scikit-learn, imblearn, SHAP for explainability, GitHub Actions CI for automated retraining

---

### 3️⃣ [Customer Churn Prediction](https://github.com/KrrishKapoor/Customer-Churn-Prediction-ML-Business-Analysis))  

**Problem**  
Digital-bank customers who exit in their first year wipe out CAC and cut future cross-sell. Knowing who’s at risk lets retention teams intervene with targeted offers.

**End-to-end pipeline**  
* **Exploratory Data Analysis** – demographics, tenure, product usage, call-center sentiment  
* **Feature engineering** – tenure buckets, transactions per active month, product-cross-usage ratios  
* **Model stack** – baseline Logistic Reg ➜ Random Forest ➜ tuned **XGBoost** ensemble (accuracy 86 %, ROC-AUC 0.91)  
* **Interpretability** – SHAP waterfall plots for execs, top drivers: low tenure, high call-center complaints, low debit usage  
* **Business scenario modeling** – retention offer costs vs. incremental lifetime value; strategy boosts net CLV **+\$58 per at-risk customer** vs. do-nothing.

**Tech & skills**  
`Python`, sklearn, XGBoost, matplotlib & seaborn visuals, Jupyter → executive PowerPoint

---

## 🧰 Skills & Tools

| Category | Stack & Methods |
|----------|-----------------|
| **Languages** | R · Python · SQL · Excel/VBA |
| **Analytics & Modeling** | Machine Learning · Monte Carlo simulation · Regression & Classification · Forecasting · Financial modeling · Optimization |
| **Visualization** | Tableau · Power BI · ggplot2 · Matplotlib |
| **Databases** | PostgreSQL · FileMaker Pro · ER modeling (3NF) |
| **Workflow** | Git & GitHub · GitHub Actions · VS Code · Markdown |
| **Soft skills** | Data storytelling · Risk analysis · Business strategy · Public speaking |

---

## 🏆 Highlights

- 🥇 **1st Place** – Rentwise Startup Pitch Competition  
- 🏆 **Winner** – Schulich Data Analytics Case (Meta & Twitter growth)  
- 💼 **Business Analyst Intern** – UPS Canada (2023)

---

## 📫 Let’s Connect

- **Email** krrishkapoor3103@gmail.com  
- **LinkedIn** <https://linkedin.com/in/krrishkapoorr>  
- **Location** Toronto, ON  

> *“Data is just the beginning. It’s the story you tell with it that creates real impact.”*
