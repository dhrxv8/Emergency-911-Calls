# 911 Emergency Calls Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## Overview

This project performs exploratory data analysis on 911 emergency calls from Montgomery County, Pennsylvania. The goal is to identify patterns in emergency categories, call timing, and geographic concentration using Python-based data analysis and visualization tools.

## Key Findings

- EMS calls account for the highest volume, followed by Traffic and Fire incidents.
- Call volume peaks between 3 PM and 6 PM on weekdays.
- Fridays show the highest average call volume across categories.
- Some zip codes consistently show higher emergency activity than others.

## Dataset

- Source: [Kaggle - 911 Calls Dataset](https://www.kaggle.com/datasets/mchirico/montcoalert)
- Geography: Montgomery County, Pennsylvania
- Records: approximately 660,000 911 call records
- Fields: `lat`, `lng`, `desc`, `zip`, `title`, `timeStamp`, `twp`, `addr`, `e`

## Analysis Included

- Emergency category breakdowns across EMS, Traffic, and Fire calls
- Time-based trends by hour, day of week, and month
- Geographic patterns by township and zip code
- Visual exploration using Matplotlib and Seaborn

## Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Core programming language |
| pandas | Data cleaning and analysis |
| Matplotlib | Static visualizations |
| Seaborn | Statistical visualizations |
| Jupyter Notebook | Interactive analysis environment |

## Project Structure

```text
Emergency-911-Calls/
├── Emergency - 911 Calls.ipynb
├── requirements.txt
└── README.md
```

## Getting Started

```bash
git clone https://github.com/dhrxv8/Emergency-911-Calls.git
cd Emergency-911-Calls
pip install -r requirements.txt
jupyter notebook "Emergency - 911 Calls.ipynb"
```

## Author

Dhruv Rao - [GitHub](https://github.com/dhrxv8)
