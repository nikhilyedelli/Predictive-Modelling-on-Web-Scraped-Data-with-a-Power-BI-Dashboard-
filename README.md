# 📊 Predictive Modelling & Analytics on Web-Scraped Data

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F79A3E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)

An end-to-end Data Analytics and Machine Learning pipeline that extracts unstructured web data, cleans and transforms it, builds predictive machine learning models, and presents actionable insights through an interactive Power BI executive dashboard.
📌 Project Overview
This project demonstrates a complete real-world data pipeline, taking raw web data from extraction to predictive intelligence and visual delivery.

By building a custom web scraper, gathering over 1,000+ unstructured records, applying rigorous data preprocessing, and modeling key patterns, this project bridges the gap between raw data collection, machine learning predictions, and business decision-making.

🔑 Key Features & Technical Workflow
1. 🕷️ Web Scraping & Data Extraction
Developed a custom Python web scraper (using BeautifulSoup / Requests / Selenium) to collect 1,000+ records from public web sources.

Automated dynamic content extraction and handled pagination, rate limiting, and raw structure parsing.

2. 🧹 Data Cleaning & Preprocessing
Handled missing data, duplicate entries, structural inconsistencies, and invalid data types using Pandas.

Applied text normalization, feature scaling, and categorical encoding to prepare the dataset for statistical modeling.

3. 🔍 Exploratory Data Analysis (EDA)
Performed deep univariate, bivariate, and multivariate analysis using Matplotlib and Seaborn.

Uncovered key patterns, seasonal trends, feature correlations, and data anomalies to inform model selection.

4. 🤖 Predictive Machine Learning Model
Built and evaluated predictive models (Classification / Regression / Clustering) using Scikit-Learn.

Performed feature selection, hyperparameter tuning, and cross-validation.

Evaluated models using industry-standard metrics (RMSE, R², Accuracy, Precision, Recall, F1-Score) to ensure reliable prediction accuracy.

5. 📊 Interactive Power BI Dashboard
Designed a clean, multi-page Power BI Dashboard to visualize both historical trends and machine learning model outputs.

Integrated dynamic filters, KPI cards, and custom visual layouts for intuitive executive reporting.

🛠️ Tech Stack & Tools
Data Extraction: Python (BeautifulSoup, Requests, Selenium)

Data Processing & EDA: Pandas, NumPy, Matplotlib, Seaborn

Machine Learning: Scikit-Learn

Business Intelligence & Visualization: Power BI, DAX, Power Query

Version Control: Git, GitHub

📈 Dashboard Preview & Highlights
Include a screenshot or GIF of your Power BI Dashboard here!

Example path: ![Dashboard Snapshot](assets/dashboard_preview.png)

KPI Summary Cards: Quick view of total records, key metrics, and predicted outcomes.

Trend Analysis: Visual representation of historical patterns vs. predicted forecasts.

Interactive Slicers: Filter insights by date, category, region, or segment.

📁 Repository Structure
Plaintext
├── assets/                  # Dashboard screenshots and images
├── data/
│   ├── raw/                 # Scraped raw dataset (1,000+ records)
│   └── processed/           # Cleaned and engineered dataset
├── notebooks/               # Jupyter Notebooks for Scraping, EDA & Modeling
│   ├── 01_web_scraper.ipynb
│   ├── 02_data_cleaning_eda.ipynb
│   └── 03_predictive_modeling.ipynb
├── dashboard/               # Power BI Report (.pbix file)
├── src/                     # Modular Python scripts
│   ├── scraper.py
│   ├── data_preprocessing.py
│   └── model.py
├── requirements.txt         # Project dependencies
└── README.md                # Project documentation
🚀 How to Run This Project
1. Clone the Repository
Bash
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
cd your-repo-name
2. Set Up Environment & Install Dependencies
Bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
3. Run the Web Scraper & Pipeline
Bash
python src/scraper.py
python src/data_preprocessing.py
python src/model.py
4. Explore the Dashboard
Open the .pbix file located in the dashboard/ folder using Power BI Desktop to interact with the visual report.

💡 Key Business Insights Derived
Identifies critical feature drivers impacting target predictions.

Transforms raw, unorganized web data into usable business intelligence.

Enables dynamic decision-making by combining machine learning outputs with visual dashboards.
