# HR Employee Attrition Analysis
An HR analytics project analyzing employee attrition drivers using Python, SQL, and Excel on the IBM HR dataset.

# 📊 Overview
This project analyzes 1,470 employee records to identify what drives employee attrition — department, tenure, income, and job satisfaction — and presents findings through an interactive Excel dashboard.

# 🛠️ Tools Used
- **Python (Pandas)** – Data loading and exploratory analysis
- **SQL (SQLite)** – KPI queries (attrition rate by department, income comparisons)
- **Excel/WPS** – Pivot tables, conditional formatting, interactive slicers
- **Google Colab** – Development environment

# 📁 Dataset
IBM HR Analytics Employee Attrition dataset (public, via Kaggle) — 1,470 employee records covering department, income, tenure, satisfaction, and attrition status.

# 🔍 Methodology
1. Loaded and inspected the dataset in Python (Pandas) — confirmed no missing values
2. Calculated attrition rate overall and by department using Pandas and SQL
3. Compared income, tenure, and job satisfaction between employees who left vs. stayed
4. Built an Excel pivot table with conditional formatting to visualize department-level attrition rate
5. Added an interactive slicer to filter the analysis by department

# 💡 Key Insights
- **Overall attrition rate: 16.1%** (237 out of 1,470 employees)
- **Sales has the highest attrition rate (20.6%)**, followed by HR (19.0%), while R&D is lowest (13.8%)
- **Employees who left earned ~30% less** on average (₹4,787 vs ₹6,833 monthly income) than those who stayed
- **Employees who left had ~2.2 fewer years of tenure** on average (5.13 vs 7.37 years), pointing to early-tenure attrition risk
- **Sales employees with less than 2 years of tenure had a 39.3% attrition rate** — nearly 2.5x the company-wide average
- Job satisfaction showed only a modest difference between groups (2.78 vs 2.47 on a 4-point scale)

# 📂 Files
- `Untitled1.ipynb` – Python/Pandas exploratory analysis and SQL KPI queries
- `HR_Attrition_Analysis.xlsx` – Excel pivot table with conditional formatting and department slicer

# 👤 Author
Harsh.
