![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)

# Personal Savings Budget Tracker 💰📊

A complete end-to-end data analysis project that simulates real-world personal finance tracking — from raw, messy CSV data to a professional, bank-style financial summary report. Built with Python and pandas, this project demonstrates skills directly applicable to banking and financial services.

---

## 📌 Project Overview

This project walks through the full data analysis lifecycle using a simulated personal finance dataset. It covers data generation, cleaning, aggregation, feature engineering, visualization, and automated reporting — all within a financial domain context.

**Core question this project answers:**
> *How can data analysis tools be used to track personal financial health, identify spending patterns, and communicate insights in a professional banking format?*

---

## 🎯 Project Objectives

| # | Objective |
|---|-----------|
| 1 | Build a real-world personal finance dataset using CSV and simulate common data quality issues |
| 2 | Load and inspect raw financial data using pandas |
| 3 | Clean the dataset using median imputation and duplicate removal |
| 4 | Parse and format date columns for time-series analysis |
| 5 | Calculate monthly income, expense, and savings totals |
| 6 | Derive a monthly savings rate percentage |
| 7 | Perform category-wise expense breakdown |
| 8 | Engineer a running savings balance column |
| 9 | Visualize expense patterns using a grouped bar chart |
| 10 | Represent savings vs. spending proportions using a pie chart |
| 11 | Plot 12-month cumulative savings growth with annotations |
| 12 | Combine all three charts into a single financial summary dashboard |
| 13 | Generate an automated Markdown report formatted as a client-facing bank document |
| 14 | Demonstrate end-to-end data analysis skills relevant to banking and financial services |

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Libraries:**
  - `pandas` — data loading, cleaning, aggregation
  - `numpy` — numerical operations and imputation
  - `matplotlib` — data visualization and dashboard layout
  - `datetime` — date parsing and formatting
  - 
---

## 🔄 Project Workflow

```
Raw CSV Data
     │
     ▼
Data Inspection (shape, dtypes, null counts)
     │
     ▼
Data Cleaning (median imputation, duplicate removal, date parsing)
     │
     ▼
Monthly Aggregation (income, expenses, savings)
     │
     ▼
Feature Engineering (savings rate %, running savings balance)
     │
     ▼
Category-wise Expense Breakdown
     │
     ▼
Visualization (bar chart → pie chart → line chart → dashboard)
     │
     ▼
Automated Markdown Report (client-facing bank document)
```

---

## 📊 Key Features

### 1. Data Simulation & Cleaning
- Generated a 12-month personal finance dataset with intentional missing values and duplicate entries
- Applied **median imputation** for null values to avoid skewing distributions
- Removed exact duplicate rows and standardized date formats

### 2. Financial Analysis
- Computed **monthly income, expenses, and net savings**
- Derived a **monthly savings rate (%)** to measure financial discipline over time
- Identified **top spending categories** using group-by aggregation

### 3. Feature Engineering
- Engineered a **running savings balance** column using cumulative sum — tracks total financial growth month by month

### 4. Visualizations

| Chart | Purpose |
|-------|---------|
| Bar Chart | Category-wise expense breakdown across the year |
| Pie Chart | Proportion of savings vs. total spending |
| Line Chart | 12-month cumulative savings growth with annotations |
| Dashboard | All three visualizations combined in a single figure |

### 5. Automated Report
- Generated a structured Markdown report with key metrics, findings, and recommendations
- Formatted as a **client-facing bank document** — ready to present to a financial audience

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib
```

### Run the Analysis
```bash
# Clone the repository
git clone https://github.com/your-username/personal-savings-budget-tracker.git
cd personal-savings-budget-tracker

# Install dependencies
pip install -r requirements.txt

# Run the full analysis
jupyter notebook notebooks/budget_tracker_analysis.ipynb
```

---

## 📈 Sample Results

**Monthly Savings Rate:** Ranged from ~18% to ~34% across the 12 months

**Top 3 Expense Categories:**
1. Housing / Rent
2. Food & Groceries
3. Transportation

**End-of-Year Cumulative Savings:** Tracked using the engineered running balance column

*(See `/outputs/` folder for all charts and the full generated report)*

---

## 💡 Key Learnings

- Real-world financial data is messy — robust cleaning pipelines are essential before any analysis
- Savings rate as a derived metric is more insightful than raw savings figures alone
- Category-level breakdowns reveal spending patterns that totals hide
- Communicating findings in a professional, client-ready format is as important as the analysis itself

---

## 🏦 Relevance to Banking & Financial Services

This project directly mirrors tasks performed in banking data roles:

- **Credit analysis teams** review income vs. expense patterns to assess borrower profiles
- **Retail banking** uses savings rate trends to offer personalized financial products
- **Data analyst roles** require end-to-end skills: raw data → clean data → insight → report
- The automated Markdown report demonstrates the ability to produce client-ready deliverables

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built as part of a data science portfolio targeting banking and financial services internships.*
