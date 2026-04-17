# MindMetrics 🧠
### Mental Health in Tech — Exploratory Data Analysis

> Analyzed 1,259 survey responses from tech workers worldwide
> to uncover treatment patterns, company culture gaps, and
> gender disparities in mental health disclosure.

[![Open Notebook](https://img.shields.io/badge/View-Analysis-7F77DD)](
https://aditisingh60.github.io/MindMetrics/)

---

## Key Findings
- **50.4%** of tech workers have sought mental health treatment
- Companies with **500+ employees** are 2x more likely to offer benefits
- Only **34%** of companies have a wellness program
- **39%** of workers fear consequences of mental health disclosure

## Visualizations
![Treatment by Company Size](charts/01_treatment_company_size.png)
![Gender Treatment Rate](charts/03_gender_treatment.png)
![Company Scorecard](charts/07_scorecard.png)

## Dataset
[OSMI Mental Health in Tech Survey](
https://kaggle.com/datasets/osmi/mental-health-in-tech-survey)
1,259 respondents | 27 features | 48 countries

## Tech Stack
`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Jupyter`

## Project Structure
MindMetrics/
├── data/           ← not tracked (add to .gitignore)
├── notebooks/
│   ├── 01_cleaning.ipynb
│   └── 02_eda.ipynb
├── charts/         ← all exported PNGs
├── index.html      ← live HTML report
└── README.md

## How to Run
pip install -r requirements.txt
jupyter notebook notebooks/02_eda.ipynb