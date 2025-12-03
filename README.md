# CUSTOMER-BEHAVIOUR-DASHBOARD
visual report that tracks how customers interact with a business over time, helping identify patterns in engagement, purchasing, and churn so decisions can be made to improve their experience.

Overview
This project analyzes customer behavior to uncover patterns that drive churn, engagement, and revenue. It covers the full analytics pipeline: loading data in Python, exploring and cleaning it, querying a MySQL database, and building an interactive Power BI dashboard for business insights.

Dataset
Source: Customer transactions and profile data (e.g., telecom customer behavior or similar domain).

Contents: Customer demographics, usage metrics, account details, and churn/behavioral flags.

Size: Replace with number of rows/columns.

Target: Replace with main outcome (e.g., “churn” / “purchase” / “subscription status”).

Tools and Technologies
Python (pandas, numpy, matplotlib/seaborn)

Jupyter Notebook

MySQL Server (and client / Workbench)

Power BI Desktop

SQL (for data extraction and transformation)

Git/GitHub for version control

Project Steps
Data Loading (Python)

Load raw CSV/Excel data into pandas DataFrames.

Inspect structure, data types, and missing values.

Exploratory Data Analysis (EDA)

Univariate analysis (distributions, summary stats).

Bivariate analysis (correlations, churn vs. key features).

Visualizations to understand trends and outliers.

Data Cleaning and Preparation

Handle missing values and inconsistent formats.

Fix data types and create derived features where needed.

Export cleaned data to MySQL for further querying.

SQL Analysis (MySQL)

Create database and tables; load cleaned data.

Write SQL queries for aggregations, segmentation, and KPIs (e.g., churn rate by plan, revenue by region).

Save query outputs for dashboard use.

Power BI Dashboard

Connect Power BI to the MySQL database (or exported tables).

Build visuals for key metrics: churn, customer segments, revenue/usage trends, and support interactions.

Add slicers/filters (e.g., region, plan type, tenure) for interactive analysis.

Dashboard
The Power BI dashboard provides:

High-level KPIs (total customers, churn rate, revenue).

Trend charts showing behavior over time.

Segmentation views (by geography, customer plan, tenure, etc.).

Drill-downs for identifying at-risk customer groups and key drivers of churn.

Results and Insights
Summarize 3–4 main findings, for example:

Most churn occurs in customers with low tenure and high support calls.

Specific plans or regions show significantly higher churn or lower revenue.

Certain features (e.g., international plan, usage patterns) strongly relate to churn or engagement.

Highlight how these insights can guide actions such as targeted retention campaigns or plan redesign.

How to Run the Project
Clone the repository

git clone <repo_url>

cd <repo_folder>

Set up Python environment

Create and activate a virtual environment (optional but recommended).

Install dependencies:

pip install -r requirements.txt

Run Python notebooks

Open the Jupyter notebooks in the notebooks/ folder.

Execute notebooks in order (01_load_data.ipynb → 02_eda_cleaning.ipynb, etc.).

Configure MySQL

Create a database (e.g., customer_behavior).

Update connection credentials in the config file or notebook.

Run the SQL script in sql/ to create tables and load cleaned data.

Open Power BI dashboard

Open the .pbix file in the powerbi/ folder.

Update the data source connection to your MySQL server.

Refresh data to view the latest results and interact with the visuals.

Reproducibility

All analysis steps from raw data to final dashboard are documented in code and SQL scripts so recruiters and collaborators can reproduce the workflow end-to-end.
