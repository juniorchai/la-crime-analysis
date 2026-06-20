# 🚔 Los Angeles Crime Analysis (2020–2022)

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python) ![Pandas](https://img.shields.io/badge/Pandas-EDA-lightblue) ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange) ![Seaborn](https://img.shields.io/badge/Seaborn-Statistical-green) ![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## Overview
Exploratory data analysis of **185,715 LAPD crime records (2020–2022)** to identify patterns in criminal behavior across Los Angeles.  
The goal is to support resource allocation decisions by uncovering when, where, and who is most affected by crime.

*Data source: Los Angeles Open Data (modified version via DataCamp)*

## Research Questions
| # | Question |
|---|----------|
| 1 | Which hour has the highest frequency of crimes? |
| 2 | Which LAPD division has the most night crimes (10pm–3:59am)? |
| 3 | Which age group is most frequently victimized? |
| 4 | What are the most common crime types? |
| 5 | Which divisions have the highest total crime count? |
| 6 | What is the gender breakdown of victims? |
| 7 | What weapons are most commonly used? |

## Key Findings
- 🕛 **12:00 noon** is peak crime hour — **13,663 incidents**
- 🌙 **Central Division** leads in night crimes and total crime overall
- 👤 **Ages 26–34** are most victimized (47,470 cases)
- 🪪 **Theft of Identity** is the #1 crime type (22,670 cases)
- ⚖️ Victim gender is nearly equal: Male 50.1% vs Female 48.4%
- ✊ When weapons were used, **bodily force** was most common

## Visualizations
| Chart | Insight |
|-------|---------|
| Crime by hour (bar) | Noon peak + midnight spike |
| Night crimes by division (bar) | Central leads |
| Victims by age group (bar) | 26–34 most affected |
| Top 10 crime types (bar) | Identity theft dominates |
| Total crimes by division (bar) | Central vs rest of city |
| Victims by gender (bar) | Near-equal split |
| Top weapons used (bar) | Bodily force most common |

## Tools & Libraries
- **Python 3.9** · **Pandas** · **NumPy** · **Matplotlib** · **Seaborn**

## Dataset
`crimes_sample.csv` — 5,000-row sample for demonstration purposes.  
Full dataset (185,715 rows) available at [LA Open Data](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8)

## How to Run
```bash
git clone https://github.com/junior-wong/la-crime-analysis
cd la-crime-analysis
pip install pandas numpy matplotlib seaborn
jupyter notebook la_crimes_extended.ipynb
```

---
*Part of my Data Analytics Portfolio — [github.com/junior-wong](https://github.com/junior-wong)*
