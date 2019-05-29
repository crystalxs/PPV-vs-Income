# Potentially Preventable Emergency Visit (PPV) Rates v.s. Income

## Table of Content

- [Project Goal](#goal)
- [Data Source](#source)
- [Exploratory Data Analysis](https://docs.google.com/document/d/1kwXIztnYbjfju0v7osqFrYqOxr3-E5eCLpB7uJw3Bag/edit?usp=sharing)
  - [Data Cleaning](<https://github.com/crystalxs/PPV-vs-income/blob/master/preprocessing.ipynb>)
  - [EDA](<https://github.com/crystalxs/PPV-vs-income/blob/master/preprocessing.ipynb>)
- Visualizations
  - [Dashboard](<http://bl.ocks.org/crystalxs/raw/fefbdc8532204b591866ce17f6f25614/>) [d3.js]
  - [Boxplot](<http://bl.ocks.org/crystalxs/raw/8020c7705ebb9f969d104d868dbaa0f7/>) [echarts.js]
  - [Heatmap](<http://bl.ocks.org/crystalxs/raw/35eecc7457e88fd5147075da17a5adfe/>) [echarts.js]
  - [Scatter plot](<http://bl.ocks.org/crystalxs/raw/251c802fba71380e50b443eb8de9c627/>) [echarts.js]
  - [Stacked Area plot](<http://bl.ocks.org/crystalxs/raw/bf6a5fe73c5c904f011116199de5596a/>) [echarts.js]
  - Chloroplethmap [Tableau]
  - Bubble Map [Tableau]
  - Histogram [Tableau | matplotlib]
  - Treemap [matplotlib]
- [Summary](#Summary)
## Project Goal <a name="goal"/>

For this project, I tried to see whether the low-income class has a higher preventable emergency visits rate.

## Data Source <a name="source"/>

There are two kinds of datasets. One is a **potentially preventable emergency visit rates** that includes a list of PPV rates for each county in NY states. The other is a **income tax** that includes income class, number of returns for each county in NY states.

- **Potentially Preventable Emergency Visit Rates**
  - [All-Payer Potentially Preventable Emergency Visit (PPV) Rates by Patient County](https://health.data.ny.gov/Health/All-Payer-Potentially-Preventable-Emergency-Visit-/f8ue-xzy3)
  - [Medicaid Potentially Preventable Emergency Visit (PPV) Rates by Patient County](https://health.data.ny.gov/Health/Medicaid-Potentially-Preventable-Emergency-Visit-P/cr7a-34ka)
- **Income Tax**
  - [Income Tax Components of Full-Year Residents by Size of Income and County](https://data.ny.gov/Government-Finance/Income-Tax-Components-of-Full-Year-Residents-by-Si/5kgr-h5g5)

## Summary

The lower income people are more likely to put off getting care until it is too late to avoid: over 90% county of New York States has higher PPV rate among Medicaid patients than average.
