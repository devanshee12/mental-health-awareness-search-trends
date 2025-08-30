# 🧠 Mental Health Awareness through Search Trends

This project analyzes **Google search interest** in mental-health topics (e.g., “therapy near me”, “stress management”, “anxiety symptoms”) and connects it with **public health statistics** to surface **awareness, stigma, and resource gaps**.

## Why this matters
Search behavior is a real-time signal of **need and awareness**. Linking it with WHO/OWID indicators can guide outreach, resourcing, and policy.

## Data sources
- Google Trends via `pytrends` (unofficial wrapper).  
- WHO Global Health Observatory (prevalence & capacity indicators).  
- Our World in Data (mental health prevalence & burden).  

## Tech stack
Python · Pandas · PyTrends · Matplotlib/Seaborn · Plotly · Jupyter · (Streamlit optional)

## Repository structure
data/
raw/         # downloaded CSVs
processed/   # cleaned/merged CSVs
notebooks/     # EDA & analysis notebooks
scripts/       # reusable data collection/cleaning scripts
visuals/       # exported charts & maps
dashboard/     # (optional) Streamlit app files
## Getting started
1) Open in GitHub Codespaces  
2) `pip install -r requirements.txt`  
3) Run notebooks in `notebooks/`

## Roadmap
- Collect Trends time-series + regional interest
- Pull WHO/OWID indicators
- Clean/merge + correlations & clusters
- Insightful visuals + (optional) Streamlit dashboard
- Write a concise policy-oriented summary

## License
MIT

Helpful references:
	•	PyTrends (unofficial Google Trends API).(https://github.com/GeneralMills/pytrends?utm_source)  ￼
	•	WHO Global Health Observatory – Mental Health ￼(https://www.who.int/data/gho/data/themes/mental-health?utm_source)
	•	Our World in Data – Mental Health (https://ourworldindata.org/mental-health?utm_source)
    