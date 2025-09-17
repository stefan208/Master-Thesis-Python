
# 📊 Inflation Beta Portfolios & Factor Model Analysis

This repository contains the Python code used for my MSc Financial Economics thesis at Erasmus University Rotterdam. The project focuses on:

1. Constructing equity portfolios based on their **inflation sensitivity** (inflation betas)  
2. Analyzing monthly portfolio returns using **OLS regression** against inflation  
3. Applying the **Fama–French 5-factor model** to assess explanatory power for inflation-driven returns

---

## 🧠 Key Objectives

- Quantify how different U.S. stocks react to inflation changes  
- Group stocks into 20 portfolios based on estimated **inflation betas**  
- Evaluate **inflation’s impact** on each portfolio’s return  
- Benchmark performance using the **Fama–French 5-factor model**

---

## 📁 Expected Data Structure (for context)

Although input files are not included in this repository, the code expects the following:

1. A main Excel file with:
   - Monthly **stock prices** (columns)
   - A **Date** column
   - An **Inflation** column

2. A second file with:
   - **Monthly portfolio returns** (20 portfolios constructed based on inflation betas)
   - A column for **inflation**

3. A third file with:
   - The **same portfolio returns** as in (2)
   - **Fama–French 5 factor data** for each period

These inputs were used in my MSc thesis to analyze inflation exposure and asset pricing relationships.

---

## ▶️ Code Structure

This repository is intended for review and demonstration purposes.  
The code can be run locally by anyone with similar structured data.  
It is organized into:

1. **Part 1:** Estimate stock-level inflation betas  
2. **Part 2:** Build and evaluate beta-sorted portfolios  
3. **Part 3:** Run regressions using Fama–French 5-factor model

---

## ▶️ How to Use

1. Clone the repository or download the `.ipynb` or `.py` file  
2. Place the required Excel files in your working directory  
3. Run the script step by step in Jupyter Notebook (or Python)  
4. Review printed regression summaries and exported results

---

## 📈 Outputs

- `inflation_betas.csv` → estimated inflation sensitivity for each stock  
- `monthly_portfolio_returns.xlsx` → equal-weighted returns of 20 portfolios  
- Terminal output with full OLS regression results for:
  - **Inflation impact** on returns  
  - **Fama–French factor exposure** for each portfolio

---

## 💬 Author

**Stefan Radovic**  
MSc Financial Economics – Erasmus University Rotterdam  
📧radovicstefan480@gmail.com

