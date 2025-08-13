# COVID-19 Global Data Analysis Report
---
## 🚀 Project Overview

This project provides a comprehensive analysis of the global COVID-19 pandemic, focusing on cases, deaths, and vaccination progress. Using the latest dataset from [Our World in Data](https://ourworldindata.org/covid-cases), we explore trends for selected countries — **Kenya, United States, and India** — and generate actionable insights through visualizations and summary statistics.

The analysis is designed to help users understand:
- How COVID-19 cases and deaths evolved over time  
- Daily new cases trends and peaks  
- Death rates and their changes over time  
- Vaccination progress and coverage across countries  
- Key insights derived from the data  

---

## 🗂️ Dataset

- **Source:** [Our World in Data COVID-19 Dataset](https://github.com/owid/covid-19-data/tree/master/public/data)  
- **File Used:** `owid-covid-data.csv`  
- **Description:** Contains daily COVID-19 metrics by country, including total cases, deaths, recoveries, and vaccinations.

---

## 🛠️ Tools & Libraries

- **Python 3.x**  
- **pandas** — data manipulation and analysis  
- **numpy** — numerical operations  
- **matplotlib** — visualization  
- **matplotlib.backends.backend_pdf** — export figures to PDF  

Optional (for enhanced visualizations):
- seaborn — for stylish plots  
- plotly / geopandas — for choropleth and interactive maps  

---

## 📊 Project Structure

covid-analysis/

├── covid_analysis.ipynb # Jupyter notebook with all code, plots, and markdown explanations

├── covid_analysis_report.pdf # Generated PDF report with visualizations and insights

├── owid-covid-data.csv # COVID-19 dataset (downloaded)

└── README.md # This file


---

## 📝 How to Run

1. Clone the repository:

```bash
git clone <repository-url>

cd covid-analysis

##2. Ensure the dataset owid-covid-data.csv is in your working directory.

##3. Install required libraries:

pip install pandas numpy matplotlib

##4. Run the Jupyter notebook or Python script:

jupyter notebook covid_analysis.ipynb

## OR

python covid_analysis.py

---

##5. The analysis will produce covid_analysis_report.pdf with all figures and key insights.

🔍 Key Analyses & Visualizations

Total Cases Over Time — line chart

Total Deaths Over Time — line chart

Daily New Cases (7-day rolling average) — line chart

Death Rates Over Time — line chart

Vaccination Progress — line chart

Latest Totals Comparison — bar chart

---

##Summary & Insights — narrative page in PDF

💡 Key Insights

USA has the highest total cases and deaths among selected countries.

Death rates decline over time after initial peaks, showing pandemic management progress.

Kenya shows smaller waves compared to India and the USA.

Vaccination rollout varies; USA leads in total vaccinated population.

Trends & patterns are useful for policymakers, health authorities, and the general public to monitor and respond to COVID-19 developments.

---

##📄 Deliverables

covid_analysis_report.pdf — Comprehensive report with plots and insights

Jupyter Notebook — Fully reproducible analysis with code and explanations

Cleaned dataset ready for further analysis

##🌟 Contributing

Contributions, suggestions, and improvements are welcome. Please submit a pull request or open an issue for discussion.

##📧 Contact

Ayodele Odugbile — drolalekan.ayodele@gmail.com
