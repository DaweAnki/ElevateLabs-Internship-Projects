# 📊 HR Analytics — Employee Attrition Prediction

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?logo=powerbi)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikit-learn)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> A complete end-to-end HR Analytics project to understand, visualize, and predict employee attrition using Exploratory Data Analysis, Machine Learning, and Power BI.

---

## 📌 Problem Statement

A company has **1,470 employees**. Every few months, some employees resign — and the company doesn't know why or who will leave next. Each resignation costs the company lakhs in hiring and training.

**Goal →** Use data science to find **why** employees are leaving and **predict** who will leave next.

---
## 📁 Project Structure
```HR-Attrition-Analysis/
│
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   └── 02_ML_Model.ipynb
│
├── outputs/
│   └── (10 EDA charts + confusion matrix + feature importance)
│
├── powerbi/
│   ├── hr_attrition_dashboard.pbix
│   └── hr_attrition_dashboard.pdf
│
└── report/
├── HR_Attrition_Prevention_Report.pdf
└── HR_Attrition_Final_Report.pdf
```
---

## 📊 Dataset

| Property | Value |
|---|---|
| Source | IBM HR Analytics (Kaggle) |
| Rows | 1,470 employees |
| Columns | 35 features |
| Target | Attrition (Yes / No) |
| Missing Values | None |
| Attrition Rate | 16.12% |

---

## 🔍 Key Findings

| # | Finding |
|---|---|
| 1 | Employees who work **overtime** leave nearly 2x more |
| 2 | **Low salary** (Rs. 2,500–5,000) is the #1 financial driver |
| 3 | **Age group 28–35** has the highest attrition count |
| 4 | **Sales department** has disproportionately high attrition |
| 5 | Employees with **no promotion in 2+ years** are high risk |
| 6 | **Work-life balance score 3** has the most resignations |

---

## 🤖 Machine Learning Model

| Property | Value |
|---|---|
| Algorithm | Random Forest Classifier |
| Train/Test Split | 80% / 20% |
| Accuracy | **88.1%** |
| Top Predictor | Monthly Income |
| 2nd Predictor | OverTime |
| 3rd Predictor | Age |

---

## 📈 Power BI Dashboard

3-page interactive dashboard with —

- **Page 1 — Overview** → KPI cards, Attrition by Department, Gender, Age
- **Page 2 — Attrition Analysis** → Overtime, Job Role, Salary, Satisfaction
- **Page 3 — Employee Details** → Data table, Key Insights, Promotion, Work-Life Balance

Features —
- 4 DAX measures (Total Employees, Attrition Count, Attrition Rate %, Avg Income)
- Department and Gender slicers
- Navigation buttons with active page highlighting

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and ML |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | EDA visualizations |
| Scikit-learn | Random Forest model |
| Power BI Desktop | Interactive dashboard |
| DAX | Custom KPI measures |
| ReportLab | PDF report generation |
| GitHub + VS Code | Version control |

---

## 📦 Deliverables

- ✅ `01_EDA.ipynb` — Exploratory Data Analysis with 10 charts
- ✅ `02_ML_Model.ipynb` — Random Forest Model (88.1% accuracy)
- ✅ `hr_attrition_dashboard.pbix` — 3-page Power BI Dashboard
- ✅ `HR_Attrition_Prevention_Report.pdf` — 8-page prevention report with 6 recommendations
- ✅ `HR_Attrition_Final_Report.pdf` — 2-page final project report

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/DaweAnki/HR-Attrition-Analysis.git
cd HR-Attrition-Analysis
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn reportlab openpyxl
```

**3. Run EDA notebook**
```bash
cd notebooks
jupyter notebook 01_EDA.ipynb
```

**4. Run ML Model notebook**
```bash
jupyter notebook 02_ML_Model.ipynb
```

**5. Open Power BI Dashboard**
Open powerbi/hr_attrition_dashboard.pbix in Power BI Desktop

---

## 📋 Prevention Recommendations

Based on data analysis, six HR interventions were identified —

1. **Overtime Management Policy** — Limit overtime, introduce compensatory off
2. **Salary Review** — Benchmark and revise salaries for low-income employees
3. **Young Talent Retention Program** — Mentorship and fast-track career paths
4. **Promotion & Recognition Cycles** — Review every 12-18 months
5. **Work-Life Balance Initiatives** — Flexible hours, hybrid work options
6. **Predictive Alert System** — Use ML model to flag at-risk employees monthly

---

## 👩‍💻 Author

**Ankita Daweshar**
Data Analyst Intern

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/DaweAnki)

---

## 📄 License

This project is open source and available for educational and portfolio purposes.
