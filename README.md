# Workforce-Capacity-Planning-Forecasting-Analytics-Platform

## Project Overview
This project simulates an **enterprise-scale workforce analytics pipeline** using official datasets from the U.S. Bureau of Labor Statistics (BLS).  
It demonstrates skills in **data engineering, data science, and business intelligence**, aligned with real-world practices at JPMC.

The platform integrates multiple messy datasets to analyze **workforce demand, productivity trends, and forecasting metrics**, while providing **Tableau dashboards and Python workflows** to monitor KPIs, identify performance gaps, and support strategic decisions.

---

## Objectives
- Ingest and clean **multi-source datasets** (OEWS, QCEW, LAUS).
- Build SQL/Databricks-style tables for **workforce demand, productivity trends, and forecasting metrics**.
- Develop **Python workflows** for KPI monitoring and forecasting.
- Create **Tableau dashboards** to visualize workforce insights and support decision-making.

---

## Datasets Used
1. **Occupational Employment and Wage Statistics (OEWS)** – 2009–2025  
   - Occupation-level employment counts and wage estimates.  
2. **Quarterly Census of Employment and Wages (QCEW)** – 2020–2022  
   - Industry-level employment and wage data.  
3. **Labor Force Participation (LAUS)** – Iowa Local Area Statistics  
   - Labor force participation rates, unemployment, and attrition trends.  

---

## Tech Stack
- **Python**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn  
- **SQL / Databricks**: Bronze → Silver → Gold pipeline design  
- **Tableau**: KPI dashboards and visualizations  
- **GitHub**: Version control and recruiter showcase  

---

## Key Features
- **Data Cleaning & Validation**  
  - Handle missing values, inconsistent codes, mixed formats.  
  - Standardize occupation codes, NAICS industry codes, and regional identifiers.  

- **Workforce Demand Analysis**  
  - Employment trends by occupation and industry.  
  - Growth rates and demand forecasting.  

- **Productivity Trends**  
  - Wage growth analysis.  
  - Attrition and participation rate tracking.  

- **Forecasting Metrics**  
  - Time-series forecasting of workforce demand and participation.  
  - Predictive modeling using ARIMA, Prophet, and Scikit-Learn.  

- **KPI Dashboards**  
  - Visual insights into performance gaps.  
  - Decision support for workforce planning.  

---

## Project Structure
Workforce-Capacity-Planning/
│
├── data/                     # Raw datasets (large files, ignored in GitHub)
│   ├── oews.csv
│   ├── employment_industry.csv
│   └── labor_force.csv
│
├── notebooks/                # Jupyter/Colab notebooks
│   ├── 01_data_ingestion.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_exploratory_analysis.ipynb
│   ├── 04_feature_engineering.ipynb
│   └── 05_modeling_forecasting.ipynb
│
├── scripts/                  # Python scripts for modular workflows
│   ├── ingestion.py
│   ├── cleaning.py
│   ├── kpi_calculations.py
│   └── forecasting.py
│
├── dashboards/               # Tableau / Power BI exports or screenshots
│   └── workforce_kpis.twbx
│
├── results/                  # Final outputs, charts, reports
│   ├── cleaned_data.csv
│   ├── kpi_summary.xlsx
│   └── forecasting_results.png
│
├── README.md                 # Project overview for recruiters
├── requirements.txt          # Python dependencies
└── .gitignore                # Ignore large raw data files

Code

---

## Sample KPIs
- Workforce demand growth rate  
- Average wage by occupation/industry  
- Labor force participation trends  
- Forecasted attrition risk  

---

## Recruiter Alignment
This project directly supports résumé bullet points:
- **Built SQL and Databricks datasets** to analyze workforce demand, productivity trends, and forecasting metrics.  
- **Developed Tableau dashboards and Python workflows** to monitor KPIs, identify performance gaps, and support decisions.  

---

## Example Workflow
1. **Data Ingestion**  
   - Load OEWS, QCEW, and LAUS datasets into Pandas/Databricks.  

2. **Data Cleaning**  
   - Handle missing values, inconsistent codes, and mixed formats.  
   - Standardize categorical fields (occupation codes, NAICS industry codes, region identifiers).  

3. **Exploratory Analysis**  
   - Identify workforce demand trends.  
   - Analyze wage growth and participation rates.  

4. **Feature Engineering**  
   - Create derived metrics (growth rates, attrition ratios, participation indices).  

5. **Forecasting**  
   - Apply ARIMA/Prophet models to predict workforce demand and participation.  

6. **Visualization**  
   - Build Tableau dashboards to present KPIs and insights.  

---

## Next Steps
- Expand forecasting models (ARIMA, Prophet, LSTM).  
- Add interactive Tableau dashboards.  
- Integrate with Databricks for scalable pipelines.  
- Automate reporting workflows with Python scripts.  

---

## License
This project uses public datasets from the U.S. Bureau of Labor Statistics (BLS).  
License: [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
