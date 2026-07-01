# 🚀 Elevate Labs — Data Analyst Internship Projects

![Internship](https://img.shields.io/badge/Internship-Elevate%20Labs-blue)
![Duration](https://img.shields.io/badge/Duration-45%20Days-green)
![Projects](https://img.shields.io/badge/Projects-2%20Completed-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![PowerBI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?logo=powerbi)

> A collection of end-to-end Data Analytics and Machine Learning projects completed during a 45-day remote Data Analyst Internship at Elevate Labs.

---

## 👩‍💻 Intern

**Ankita Daweshar**
Data Analyst Intern — Elevate Labs (Remote)

[![GitHub](https://img.shields.io/badge/GitHub-DaweAnki-black?logo=github)](https://github.com/DaweAnki)

---

## 📁 Repository Structure
```
ElevateLabs-Internship-Projects/
│
├── Project 1 HR_Attrition_Project/
│   ├── data/
│   ├── notebooks/
│   │   ├── 01_EDA.ipynb
│   │   └── 02_ML_Model.ipynb
│   ├── outputs/
│   └── powerbi/
│
├── Project2 Ecommerce-Return-Rate-Analysis/
│   ├── data/
│   ├── notebooks/
│   │   ├── 01_EDA_Return_Analysis.ipynb
│   │   └── 02_ML_LogisticRegression.ipynb
│   ├── output/
│   └── reports/
│
└── README.md
```
---

## 📊 Projects Overview

| # | Project | Domain | Algorithm | Accuracy | Dashboard |
|---|---------|--------|-----------|----------|-----------|
| 1 | HR Analytics — Employee Attrition Prediction | HR Analytics | Random Forest | **88.1%** | 3-page Power BI |
| 2 | E-Commerce Return Rate Reduction Analysis | E-Commerce Analytics | Logistic Regression | **71.0%** | 4-page Power BI |

---

## 🔴 Project 1 — HR Analytics: Employee Attrition Prediction

### Problem Statement
A company has 1,470 employees. Every few months some employees resign and the company doesn't know why or who will leave next. Each resignation costs the company heavily in hiring and training.

**Goal →** Use data science to find **why** employees are leaving and **predict** who will leave next.

### Key Findings
| # | Finding |
|---|---------|
| 1 | Employees who work **overtime** leave nearly 2× more |
| 2 | **Low salary** (Rs. 2,500–5,000) is the #1 financial driver |
| 3 | **Age group 28–35** has the highest attrition count |
| 4 | **Sales department** has disproportionately high attrition |
| 5 | Employees with **no promotion in 2+ years** are high risk |

### ML Model
| Property | Value |
|---|---|
| Algorithm | Random Forest Classifier |
| Train/Test Split | 80% / 20% |
| Accuracy | **88.1%** |
| Top Predictor | Monthly Income |

### Deliverables
- ✅ `01_EDA.ipynb` — Exploratory Data Analysis with 10 charts
- ✅ `02_ML_Model.ipynb` — Random Forest Model (88.1% accuracy)
- ✅ Power BI Dashboard — 3-page interactive dashboard

---

## 🛒 Project 2 — E-Commerce Return Rate Reduction Analysis

### Problem Statement
An e-commerce company has 5,000 orders across 5 product categories. Every returned order costs ₹200 in reverse logistics and the business doesn't know which orders will be returned or why.

**Goal →** Use data science to find **why** customers are returning products, **where** returns are happening most, and **predict** which future orders are likely to be returned.

### Key Findings
| # | Finding |
|---|---------|
| 1 | Overall return rate is **29%** — nearly 1 in 3 orders returned |
| 2 | **Clothing** has the highest return rate at **37.4%** |
| 3 | **City44** is the riskiest location with a **50% return rate** |
| 4 | **Credit Card** payments have the highest return rate at 31% |
| 5 | High discounts (avg 26.8%) correlate with more returns |
| 6 | Total direct return cost is **Rs. 2,90,000** |

### ML Model
| Property | Value |
|---|---|
| Algorithm | Logistic Regression |
| Train/Test Split | 80% / 20% |
| Accuracy | **71.0%** |
| High Risk Orders | 2,406 out of 5,000 |

### Deliverables
- ✅ `01_EDA_Return_Analysis.ipynb` — EDA with 11 charts
- ✅ `02_ML_LogisticRegression.ipynb` — Logistic Regression Model
- ✅ `high_risk_products.csv` — Products with ≥40% return rate
- ✅ `high_risk_orders.csv` — Orders with risk score ≥ 0.5
- ✅ `all_orders_with_risk_scores.csv` — All 5,000 orders with risk scores
- ✅ Power BI Dashboard — 4-page interactive dashboard

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and ML |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | EDA visualizations |
| Scikit-learn | Machine learning models |
| Power BI Desktop | Interactive dashboards |
| DAX | Custom KPI measures |
| ReportLab | PDF report generation |
| GitHub + VS Code | Version control and development |

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/DaweAnki/ElevateLabs-Internship-Projects.git
cd ElevateLabs-Internship-Projects
```

**2. Run Project 1**
```bash
cd "Project 1 HR_Attrition_Project/notebooks"
jupyter notebook 01_EDA.ipynb
```

**3. Run Project 2**
```bash
cd "Project2 Ecommerce-Return-Rate-Analysis/notebooks"
jupyter notebook 01_EDA_Return_Analysis.ipynb
```

---

## 📦 All Deliverables

| Project | Deliverable | Status |
|---------|-------------|--------|
| Project 1 | EDA Notebook — 10 charts | ✅ |
| Project 1 | Random Forest Model — 88.1% accuracy | ✅ |
| Project 1 | 3-page Power BI Dashboard | ✅ |
| Project 2 | EDA Notebook — 11 charts | ✅ |
| Project 2 | Logistic Regression Model — 71% accuracy | ✅ |
| Project 2 | High-Risk Products & Orders CSVs | ✅ |
| Project 2 | 4-page Interactive Power BI Dashboard | ✅ |

---

## 📄 License

This repository is open source and available for educational and portfolio purposes.
