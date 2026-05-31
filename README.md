# Telco Customer Churn & Retention Analysis

## 📌 About
This project focuses on identifying churn patterns, retention drivers, and customer lifetime trends in a subscription-based telecommunications business. By leveraging Python for data cleaning and exploratory data analysis (EDA), SQL for structured querying, and Power BI for interactive visualizations, this analysis provides actionable insights to reduce customer attrition.

## 🚀 Features
- **Exploratory Data Analysis (EDA):** Python notebooks utilizing Pandas and data visualization libraries to uncover hidden patterns in customer demographics, services, and billing.
- **SQL Data Analysis:** Structured queries to calculate churn rates across different customer segments, contract types, and payment methods.
- **Interactive Power BI Dashboard:** A comprehensive visual report (`Telco Churn Rate`) highlighting key performance indicators (KPIs) like churn risk, monthly charges, and service adoption.
- **End-to-End Pipeline:** From raw data ingestion to processed data exports ready for reporting.

## 🛠️ Tech Stack
- **Data Processing & Analysis:** Python (Pandas, Numpy)
- **Database Querying:** SQL
- **Data Visualization:** Power BI, Matplotlib/Seaborn

## 📂 Repository Structure
- `data/`: Contains the raw dataset (`WA_Fn-UseC_-Telco-Customer-Churn.csv`).
- `exports/`: Contains the cleaned dataset (`telco_churn_cleaned.csv`) generated from the Python notebooks.
- `notebook/`: Contains Jupyter Notebooks detailing the data cleaning and EDA processes.
- `sql/`: Contains `churn_queries.sql` with SQL scripts used to extract deeper insights.
- `dashboard/`: Contains the Power BI dashboard file (`Telco Churn Rate.pbix`) and a PDF export for quick viewing.

## ⚙️ Setup and Usage
1. **Python Analysis:** 
   - Open the notebooks in the `notebook/` folder using Jupyter Notebook or VS Code.
   - Run the cells to reproduce the data cleaning and exploratory analysis.
2. **SQL Analysis:**
   - Import the `exports/telco_churn_cleaned.csv` into your preferred SQL database.
   - Run the queries found in `sql/churn_queries.sql`.
3. **Power BI Dashboard:**
   - Open `dashboard/Telco Churn Rate.pbix` using Power BI Desktop to interact with the visualizations.
   - You can also view the static report via the provided PDF in the same folder.
