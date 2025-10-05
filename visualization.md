---
layout: default
title: Data Visualizations
---
# Data Science Visualizations
## Defence Budget Analysis Project
This project analyzes India's Defence and R&D budget trends using data from data.gov.in, covering the period from 1961-62 to 2013-14.

#### 1. Line Plot - Defence Budget Trends Over Time
<img src="https://raw.githubusercontent.com/Shubhamghodake000/Defence_budget_visualization_project/main/visualization/1_line_plot.png" alt="Defence Budget Trends">

**Explanation:** This line chart tracks the evolution of India's total defence budget (blue) and R&D budget (orange) across five decades. The visualization reveals an exponential growth pattern, particularly accelerating after the 2000s, with the defence budget climbing from ₹313 Crores to over ₹2 lakh Crores.

**Observations:** Both defence and R&D budgets show exponential growth over 52 years, with total defence budget increasing from ₹313 Crores (1961-62) to ₹203,672.1 Crores (2013-14).

#### 2. Bar Plot - Year-wise Budget Comparison
<img src="https://raw.githubusercontent.com/Shubhamghodake000/Defence_budget_visualization_project/main/visualization/2_bar_plot.png" alt="Year-wise Comparison">

**Explanation:** This grouped bar chart provides a side-by-side comparison of annual defence (green) and R&D (red) budgets for each fiscal year. The visualization makes it easy to compare the relative proportions and identify periods of significant budget increases or policy shifts.

**Observations:** Side-by-side comparison reveals R&D allocations maintain a consistent proportion of total defence spending, with notable acceleration post-2000.

#### 3. Scatter Plot - Correlation Analysis
<img src="https://raw.githubusercontent.com/Shubhamghodake000/Defence_budget_visualization_project/main/visualization/3_scatter_plot.png" alt="Correlation Analysis">

**Explanation:** This scatter plot analyzes the relationship between total defence budget and R&D spending, with each point representing a fiscal year. The trend line (y = 0.0583x + 42) and exceptionally high correlation coefficient of 0.9911 demonstrate that R&D allocations are systematically proportional to overall defence expenditure.

**Observations:** Strong positive correlation (0.9954) indicates R&D budget planning is systematically tied to overall defence spending levels.

#### 4. Line Plot - R&D Percentage Trend
<img src="https://raw.githubusercontent.com/Shubhamghodake000/Defence_budget_visualization_project/main/visualization/4_percentage_trend.png" alt="R&D Percentage Trend">

**Explanation:** This area chart displays R&D budget as a percentage of total defence outlay over time, with colored regions showing periods above and below the 4.48% historical average. The visualization highlights a significant policy shift in the mid-1980s when R&D allocation jumped from 2% to consistently above 5%, peaking at 6.7% during 2007-2009.

**Observations:** R&D spending remained below 2.5% until the mid-1980s, then jumped above the 4.48% average and stabilized between 5-7% for most of the 2000s, before declining slightly to 5.2% by 2013-14.

### Key Findings
- **Average Defence Budget Change:** ₹12,033 Crores/year
- **Average R&D Budget Change:** ₹627 Crores/year
- **Average Defence Growth Rate:** 22.85% per year
- **Average R&D Growth Rate:** 25.12% per year
- **R&D as % of Defence Budget:** 4.48% (average)
- **Correlation:** 0.9954 (Strong Positive)

### Dataset Source
**Dataset:** Department of Defence R&D Budget Over the Years  
**Source:** [data.gov.in](https://data.gov.in/)

### View Complete Analysis
**GitHub Repository:** [Defence Budget Analysis Project](https://github.com/Shubhamghodake000/Defence_budget_visualization_project) 

**Project Structure:**

```
defence-budget-analysis/
│
├── Defence_budget.ipynb                    # Main Jupyter notebook with analysis
├── Departofdefence_RandD_budgetover_1.csv  # Dataset file
├── README.md                               # Project documentation
│
└── Visualization/                                  
    ├── 1_line_plot.png                    # Line plot showing budget trends
    ├── 2_bar_plot.png                     # Bar plot comparing budgets year-wise
    ├── 3_scatter_plot.png                 # Scatter plot showing correlation
    └── 4_percentage_trend.png             # R&D percentage trend over time
```
---
*Analysis performed using Python, pandas, matplotlib, and seaborn*
