# 📊 Corporate Finance Institute – Financial Reporting Dashboard

This Power BI dashboard delivers a full-spectrum financial reporting solution, built from scratch using sample data modeled after real-world corporate finance structures. It includes both **Balance Sheet** and **Income Statement** views, enabling stakeholders to assess liquidity, profitability, and capital structure across multiple periods.

---

## 🔍 Project Overview

- **Tools Used**: Azure Data Studio, Power BI Desktop, DAX Studio  
- **Domain**: Corporate Finance / Financial Reporting / FP&A  
- **Focus Areas**: Financial Statement Modeling, KPI Calculation, Time-Series Analysis, Ratio Interpretation

---

## 🧠 What I Built

- **Custom Financial Statement Modeling**:
  - Constructed both **Balance Sheet** and **Income Statement** from scratch
  - Learned and applied accounting logic to define line items:
    - *Assets*: Cash, Accounts Receivable, Inventory, PP&E, Intangibles
    - *Liabilities*: Payables, Accrued Expenses, Debt
    - *Equity*: Shareholder’s Equity
    - *Income Statement*: Revenue, COGS, Operating Expenses, Other Income/Expenses, Taxes

- **Data Loading & Transformation**:
  - Imported structured financial data using **Azure Data Studio**
  - Cleaned and transformed data using **Power Query**
  - Modeled relationships using a **snowflake schema** to reflect normalized hierarchies (e.g., Store → Region)

- **Advanced DAX Measures**:
  - KPIs: `Gross Margin Ratio`, `Operating Margin Ratio`, `Current Ratio`, `Debt Ratio`
  - Used complex DAX functions: `CALCULATE`, `SWITCH`, `DIVIDE`, `FILTER`, `ALLSELECTED`
  - Validated and optimized measures using **DAX Studio**

---

## 📈 Dashboard Features

### 🧮 Balance Sheet Dashboard
<img width="1920" height="1080" alt="Screenshot (1549)" src="https://github.com/user-attachments/assets/21ca222b-9d87-47e8-acbe-268c42fef26d" />

- Time-series analysis from **2019 Q1 to 2021 Q4**
- KPIs:
  - *Current Ratio*: 2.26
  - *Debt Ratio*: 0.04
- Visuals:
  - Line chart: *Current Ratio by Year and Quarter*
  - Bar chart: *Current Assets vs Current Liabilities*

### 📊 Income Statement Dashboard
<img width="1920" height="1080" alt="Screenshot (1548)" src="https://github.com/user-attachments/assets/7a6634bc-4905-43f2-8bcb-b539cf6731f1" />

- Covers **2019–2021**
- KPIs:
  - *Gross Margin Ratio*: 21%
  - *Operating Margin Ratio*: 5%
- Visuals:
  - Trend line: *Operating Profit*
  - Bar chart: *Expense Breakdown* (Operating, Other, Tax)

---

## 🛠️ Technical Stack

| Component         | Details                                                                 |
|------------------|-------------------------------------------------------------------------|
| Data Source       | Azure Data Studio (SQL)                                                 |
| BI Tool           | Power BI Desktop                                                        |
| ETL               | Power Query                                                             |
| Modeling          | Snowflake schema with normalized dimension hierarchies                  |
| DAX Functions     | CALCULATE, SWITCH, DIVIDE, FILTER, ALLSELECTED                          |
| Optimization      | DAX Studio for performance tuning                                       |

---

## 📌 Use Cases

- Executive dashboards for quarterly financial reviews
- FP&A reporting for internal stakeholders
- Training tool for finance professionals and students


---

## 📂 File Structure
📁 CFI_Financial_Reporting_Dashboard ├── Balance_Sheet.pbix ├── Income_Statement.pbix ├── README.md └── Screenshots/ ├── Balance_Sheet.png └── Income_Statement.png


---

## 👤 Author

**Sidharth** – Freelance Data Analyst | Banking & Retail Analytics  
📍 Based in Dubai | 💼 Actively seeking analytics roles  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/sidharth-kashyap-dataanalyst)  
📫 Reach out for collaborations or freelance projects

---

## 📣 Feedback & Contributions

Open to feedback, suggestions, and collaboration. Feel free to fork, star ⭐, or raise issues!
