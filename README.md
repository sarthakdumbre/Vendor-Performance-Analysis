🧾 Vendor Performance Analysis with EDA

📌 A data-driven analysis project focused on evaluating vendor performance through exploratory data analysis (EDA) to uncover insights that optimize purchasing and sales strategies.

📊 Overview

This project analyzes vendor performance metrics using real-world purchasing and sales data.
It combines data cleaning, transformation, and exploratory analysis to identify key trends in vendor sales, purchase quantities, pricing, and unsold stock capital.

Three primary notebooks make up the workflow:

Import.ipynb – Handles data import, cleaning, and preprocessing.

ED_Analysis.ipynb – Performs exploratory data analysis (EDA) and visualization.

Vendor_P_Analysis.ipynb – Focuses on vendor performance metrics, sales vs. purchase comparisons, and profitability insights.

🎯 Problem Statement

Organizations often face challenges in evaluating vendor efficiency and understanding how purchasing decisions impact profitability.
This project aims to:

Assess vendor-wise performance.

Identify underperforming vendors.

Quantify unsold inventory and capital lock-up.

Provide actionable insights through visual dashboards.

📂 Dataset

The dataset contains details about:

Vendor numbers, names, and brands

Purchase prices and actual sale prices

Quantities purchased and sold

Freight costs and descriptions

Each record represents transactional or summarized vendor performance data over a defined period.

🧰 Tools and Technologies

Python 3.x

Jupyter Notebook

Libraries:
pandas, numpy, matplotlib, seaborn, plotly, openpyxl

Data Visualization: Matplotlib & Plotly for interactive visual analytics

Data Source: Internal vendor and sales database (processed via SQL or CSV imports)

⚙️ Methods

Data Cleaning:

Removal of invalid/missing entries.

Data type conversions (dates, floats, etc.).

Standardization of vendor and brand names.

Exploratory Data Analysis (EDA):

Descriptive statistics and distribution checks.

Correlation heatmaps and trend visualizations.

Vendor-wise and brand-wise aggregations.

Performance Metrics Calculation:

Sales-to-purchase ratios.

Unsold capital estimation.

Freight cost impacts.

Visualization:

Interactive plots showing vendor efficiency and sales trends.

Comparative dashboards summarizing key KPIs.

🔑 Key Insights

Identification of top-performing vendors by sales and profit margin.

Detection of vendors with high unsold capital, indicating over-purchasing.

Clear visibility into brand-wise performance trends.

Insights that guide data-backed purchasing decisions.

📈 Dashboard / Model / Output

Visual dashboards highlighting vendor rankings and profitability.

Graphs showing sales vs. purchase trends.

KPI metrics for each vendor (sales ratio, capital lock, freight share, etc.).

Final summary tables providing actionable business insights.

🚀 How to Run this Project

Clone the repository:

git clone https://github.com/sarthakdumbre>/vendor-performance-analysis.git
cd vendor-performance-analysis


Install required libraries:

pip install -r requirements.txt


Open the notebooks:

jupyter notebook


Run the following notebooks in order:

Import.ipynb

ED_Analysis.ipynb

Vendor_P_Analysis.ipynb

🏁 Results & Conclusion

The project successfully demonstrates how data-driven EDA can reveal deep insights into vendor operations.
By leveraging analytical visualizations, we can:

Reduce capital lock-ups.

Improve vendor selection and pricing strategy.

Enhance overall purchasing efficiency.

🔮 Future Work

Integrate real-time vendor data through APIs.

Build a predictive model for vendor performance forecasting.

Develop an interactive Streamlit dashboard for management visualization.

Automate report generation for monthly insights.

👨‍💻 Author Contact

Shreyas Dhomase
📧 sarthakdumbre33@gmail.com
💻 GitHub:https://github.com/sarthakdumbre